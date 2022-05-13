# EKS kiel Datuma Strukturo

{{#include ../include/links.md}}

Aktualaj oficialaj ekzemploj:
[`ecs_guide`][example::ecs_guide].

Ankaŭ vizitu finitajn ludekzemplojn:
[`alien_cake_addict`][example::alien_cake_addict],
[`breakout`][example::breakout].

---

Bevy konservas kaj kontrolas tutan vian datumon por vi, uzante na la Bevy EKS
(Ent-Komponanta Sistemo).

Koncipe vi povas pensi pri ĉi tio kiel pri tabeloj, kvazaŭ en datumbazo. Viaj diversaj datumtipoj (Komponantoj) estas kiel "kolonoj" de tabelo, kie povas ekzisti arbitre multaj "vicoj" (Entoj), enhavantaj valorojn de ĉiu komponanto.

Ekzemple, vi povas krei `Health` komponanton por via ludo. Tiam vi povas havi multajn entojn, prezentantajn malsamajn aferojn en via ludo, kiel ludanto, NLRoj (Ne Ludantaj Roluloj), aŭ monstroj, ĉiuj el kiuj povas havi `Health` valoron (samkiel aliajn signifajn komponantojn).

Ĝi faciligas krei ludan logikon ([Sistemoj][cb::system]), kiu povas funkcii kun iu ento kun necesaj komponantoj (kiel sano-damaĝa sistemo por ĉio, kio havas na `Health`), sendepende de tio, ĉu ĝi estas la ludanto, NLR aŭ monstro (aŭ io ajn). Ĉi tio farigas vian ludlogikon tre reuzebla kaj universala.

La aro de komponantoj, kiujn havas donita ento, estas nomita Enta Arketipo.

NB, ke entoj ne estas limigitaj al nur "objektoj en la ludmondo". EKS estas ĝeneraluzebla datumstrukturo. Vi povas krei entojn kaj komponantojn por konservi ajnajn datumojn.

## Plenumeco

Bevy havas saĝan planad-algoritmon, kiu lanĉas viajn sistemojn paralele laŭ ebleco. Ĝi faras ĉi tion aŭtomate, kiam viaj funkcioj ne bezonas konfliktantan atingon al la sama datumo. Via ludo skalos por funkcii per pluraj CPU-kernoj "senpage"; tio estas, sen bezono de ekstra disvolva penado de vi.

Por pliigi la probablecon de samtempeco, vi povas farigi vian datumon kaj kodon pli detaligitaj. Dividu vian datumon en pli malgrandajn tipojn / `struct`-ojn. Dividu vian logikon en multajn pli malgrandajn sistemojn / funkciojn. Igu ĉiun sistemon havi atingon nur al la datumo, kiu estas aktuala por ĝi. Ju malpli da atingaj konfliktoj estos, des pli rapide via ludo funkcios.

La ĝenerala regulo de Bevy estas: ju pli da detalo, des pli bone.

## Rimarko por Programistoj, venantaj el Objekt-Orientitaj Lingvoj

Vi eble kutimis pensi laŭ "objektklasoj". Ekzemple, vi povus difini grandan monolitan `struct Player`, enhavantan ĉiujn kampojn/ecojn de la ludanto.

En Bevy, tion oni konsideras kiel malbona praktiko, ĉar fari ĉi tion povas malfaciligi laboron kun viaj datumoj kaj limigi plenumecon.

Anstataŭe, vi devus fari aferojn grajnecaj, kiam diversaj datumoj povas esti atingitaj sendepende.

Ekzemple, prezentu la Ludanton en via ludo kiel ento, kunmetita el apartaj komponantspecoj (apartaj `struct`-oj) por aferoj kiel la sano, XP, aŭ kio ajn gravas por via ludo. Vi ankaŭ povas ligi normajn Bevy-komponantojn al ĝi kiel [`Transformo`][bevy::Transform] ([klarigita ĉi tie][cb::transform]).

Ĉi tio faciligos al vi ellabori viajn sistemojn (luda logiko /
kondutoj), kaj ankaŭ plibonigi la lanĉan plenumecon de via ludo.

Tamen, io kiel [`Transform`][bevy::Transform], aŭ aro de koordinatoj, ankoraŭ havas sencon kiel ununura `struct`, ĉar ĝiaj kampoj verŝajne ne estos utilaj sendepende.
