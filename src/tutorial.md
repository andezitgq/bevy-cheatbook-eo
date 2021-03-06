# Ĉu komencanto en Bevy? Tute Gvidita Instrukcio!

{{#include ./include/links.md}}

Bonvenon al Bevy! :) Ni ĝojas vidi vin en nia komunumo!

Ankaŭ vd. [la oficialajn Bevy ekzemplojn][bevy::examples]. Se vi bezonas helpon, uzu [GitHub Diskutoj][bevy::ghdiscussions], aŭ ne timu
eniri babilejon kaj demandi por helpo en [Diskordo][bevy::discord].

---

Ĉi tiu paĝo estas por novaj lernantoj. Ĝi gvidos vin tra ĉi tiu libro en la ordo, kiu havas sencon studi, de la bazaĵoj ĝis la pli progresintaj temoj. Ĉi tio diferencas de la ĉefa enhavtabelo (maldekstra flanka kolumno), kiu estas celita esti uzata de Bevy-uzantoj de ĉiuj lertaj niveloj.

Ĉi tiu instrukcio-paĝo ne listigas ĉiujn paĝojn de la libro. Ĉi tio estas gvidilo por helpi vin akiri ampleksan ĝeneralan scion. La libro ankaŭ havas multajn paĝojn, dediĉitajn al solvoj de specifaj problemoj, kiuj ne estas listigitaj ĉi tie.

Sentu liberecon esplori la libron kaj legi ion ajn, kiu vin interesigas.

Vi faros ion mojosan kun Bevy dum mallonga tempo! ;)

---

Se vi renkontas problemojn, vizitu la
[Ĝeneralajn Kaptilojn][chapter::pitfalls] ĉapitro por vidi, ĉu ĉi tiu libro havas ion por helpi vin. Solvaĵoj al iuj el la plej oftaj problemoj de la komunumo de Bevy-membroj estas dokumentitaj tie.

## Bazaĵoj

Ĉi tiuj estas la absolutaj bazaĵoj de uzado de Bevy - la nura minimumo de konceptoj por komenci. Ĉiu projekto de Bevy, eĉ simpla, postulos, ke vi konatiĝu kun ĉi tiuj konceptoj.

Eble vi povus fari ion kiel simplan konkurs-ludon aŭ prototipon, uzante ĝuste tiun scion. Kvankam dum via projekto altiĝos, vi verŝajne devos lerni pli rapide.

 - [Konsiloj pri Bevy Instalado][chapter::setup]: Agordado de viaj ellaboliroj kaj medio
   - [Komencante][cb::getting-started]
 - [Bevy Programada Enkadraĵo (Framework)][chapter::programming]:
   Kiel skribi Bevy-kodon, strukturi viajn datumojn kaj logikon
   - [Enkonduko al EKS][cb::ecs-intro]
   - [Entoj kaj Komponantoj][cb::ec]
   - [Risurcoj][cb::res]
   - [Sistemoj][cb::system]
   - [Aplikaĵa Konstruilo][cb::app]
   - [Informpetoj][cb::query]
   - [Komandoj][cb::commands]
   - [Eventoj][cb::event]
 - [Kerno de Bevy Ludmotoro][chapter::features]:
   Bazaj apartaĵoj de Bevy, bezonataj por krei iun ajn ludon
   - [Koordinata Sistemo][cb::coords]
   - [Transformoj][cb::transform]
   - [Tempo kaj Tempigiloj][cb::time]
 - [Administrado de Valoraĵoj][chapter::assets]:
   Kiel labori kun valoraĵoj (assets)
   - [Priskribiloj (Handles)][cb::handle]
   - [Elŝuti Valoraĵojn el Dosieroj][cb::assetserver]
 - [Eniga Priskribilo][chapter::input]:
   Uzado de diversaj enigaj aparatoj
 - [Administrado de Fenestroj][chapter::window]:
   Instalado de la operaciuma fenestro (aŭ plenekrano) por via ludo
   - [Ŝanĝo la Fonkoloron][cb::clearcolor]

## Sekvaj Paŝoj

Vi verŝajne bezonos ekscii almenaŭ kelkajn el ĉi tiuj temoj por krei ne-trivialan Bevy-projekton. Post kiam vi estos komforta kun la bazaĵoj, vi povos konatiĝi kun ili por fariĝi potenca uzanto de Bevy.

 - [Konsiloj pri Bevy Instalado][chapter::setup]
   - [Ellaboriloj kaj Redaktiloj por Bevy][cb::tools]
   - [Ekosistemo de Komunumaj Kromaĵoj][cb::3rdparty]
 - [Bevy Programada Enkadraĵo (Framework)][chapter::programming]
   - [Sistema Ordo de Plenumado][cb::system-order]
   - [Sistemaj Aroj][cb::systemset]
   - [Lokaj Risurcoj][cb::local]
   - [Kromaĵoj][cb::plugin]
   - [Titoloj][cb::label]
   - [Statoj][cb::state]
   - [Detekto de Ŝanĝo][cb::change-detection]
   - [Parametraj Aroj][cb::queryset]
   - [Etapoj][cb::stage]
 - [Programadaj Ŝablonoj][chapter::patterns]
   - [Generaj Sistemoj][cb::system-generic]
   - [Komponanta Stokaĵo][cb::component-storage]
 - [Administrado de Valoraĵoj][chapter::assets]:
   - [Atingo al la Valoraĵ-datumo][cb::asset-data]
   - [Reagi al Ŝanĝoj kun Valoraĵ-eventoj][cb::assetevent]
   - [Tuj-Reŝargo de Valoraĵoj][cb::asset-hotreload]

## Progresinta Nivelo

Ĉi tiuj estas pli fakaj temoj, kiuj povas esti utilaj en kompleksaj projektoj. Plej tipaj uzantoj de Bevy ne bezonos scii ĉi tion.

 - [Bevy Programada Enkadraĵo (Framework)][chapter::programming]
   - [Lanĉaj Kriterioj][cb::runcriteria]
   - [Detekto de Forigo][cb::removal-detection]
   - [Sistema Ligado][cb::system-chain]
   - [Direkta Atingo al EKS-Mondo][cb::world]
   - [Ekskluzivaj Sistemoj][cb::exclusive]
   - [Nesendaj Risurcoj][cb::nonsend]
 - [Programadaj Ŝablonoj][chapter::patterns]
   - [Permana Event-Malplenigo][cb::event-manual]

## Solvaĵoj por Specifaj Problemoj

Ĉi tiuj estas paĝoj, kiuj instruas vin kiel solvi specifajn problemojn, kiujn vi eble
renkontiĝu en via projekto.

 - [Konverti kursoron en mondajn koordinatojn][cookbook::cursor2world]
 - [Kreado de Testoj por Sistemoj][cb::system-tests]
 - [Observi Elŝut-progreson][cb::asset-ready]
 - [Kapti la Muskursoron][cookbook::mouse-grab]
 - [Difini la Fenestran Ikoneton][cookbook::window-icon]
 - [Enigo de Teksto][input::char]
 - [Treni-k-faligi dosierojn][input::dnd]
 - [Propra Projekcio de Kamerao][cookbook::cursor2world]
