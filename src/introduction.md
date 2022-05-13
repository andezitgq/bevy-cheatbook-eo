# Neoficiala Bevy Tromplibro (de Ida Iyes)
## ATENTO: La traduko estas plenumigata laŭ ordo de la [gvidita instrukcio][chapter::tutorial]

{{#include ./include/links.md}}

Ĉi tio estas referenc-stila libro por [Bevy ludmotoro][bevy::website]([GitHub][project::bevy]).

Ĝi celas instrui Bevy konceptojn en konciza maniero, helpi vin esti produktiva, kaj malkovru la scion, kiun vi bezonas.

Ĉi tiu libro kunigas multe da komunuma saĝeco, kiu ofte ne estas kovrita per oficiala dokumentado, ŝparante al vi la bezonon lukti kun aferoj kiuj aliaj jam komprenis!

Kvankam ĝi celas esti ĝisfunda, dokumentado de tuta ludmotoro estas monumenta tasko. Mi enfokusigas mian tempon por io ajn mi kredas la komunumo plej bezonas.

Tial, estas ankoraŭ multaj preterlasoj, ambaŭ por bazaj kaj progresintaj temoj. Tamen, mi certas, ke ĉi tiu libro pruvos esti valora risurco al vi!

***Bonvenon! Ke ĉi tiu libro servu al vi bone!***

- [Cheatbook EN GitHub](https://github.com/bevy-cheatbook/bevy-cheatbook)
- [Tromplibro EO GitHub](https://github.com/andezitgq/bevy-cheatbook-eo/)
- [Patronado de Cheatbook aŭtoro](https://github.com/sponsors/inodentry)
- [Retejo de la tradukinto](https://github.com/andezitgq)

## Kiel uzi la libron

La paĝoj en ĉi tiu libro ne estas kreitaj por esti legitaj laŭvice. Ĉiu 
paĝo kovras memstaran temon. Sentu liberecon por translokiĝi al io, pri kio
vi interesiĝas.

Se vi havas specialan temon en menso, pri kiu vi ŝatus lerni, vi
povas trovi ĝin el la enhavtabelo (la flankpanelo) aŭ uzante la serĉfunkcion
(en la supra panelo).

La [Superrigardo de Ĉapitroj][chapter::overview] paĝo donos al vi ĝeneralan ideon
pri kiel la libro estas strukturita.

Se vi estas komencanto en Bevy, aŭ dezirus pli gviditan sperton, provu la [instruckio paĝon][chapter::tutorial]. Ĉi tio helpos vin navigi la libron en ordo, kiu havas sencon por lernado, de elementaj ĝis progresintaj temoj.

La [Bevy Enkonstruaĵoj][chapter::builtins] paĝo estas konciza kaŝslipeto de utila informaĵo pri tipoj kaj trajtoj, provizitaj de Bevy

## Rekomenditaj Aldonaj Risurcoj

Bevy havas riĉan kolekton de [oficialaj kod-ekzemploj][bevy::examples].

Vizitu [bevy-valoraĵojn][bevyassets], por komunume kreitaj risurcoj.

Nia komunumo estas tre amikema kaj utila. Bonvolu aliĝi al la [Bevy
Diskordo][bevy::discord] por babili, demandi aŭ partopreni en la projekto!

Se vi volas vidi kelkajn ludojn, kreitajn per Bevy, vd. [itch.io][itchio::bevy]
aŭ [Bevy Valoraĵojn][bevyassets::games].

## Prizorgado

Ĉi tiu versio de la libro estas por Bevy-eldono 0.7.

Mi intencas teni ĉi tiun libron ĝisdatigita kaj grava kun ĉiu nova eldono de Bevy.
Mi ankaŭ provas regule fari plibonigojn al ĝi, kiam mi povas administri ĝin.

## Subtenu la libraŭtoron

<a class="github-button" href="https://github.com/sponsors/inodentry" data-icon="octicon-heart" data-size="grande" aria-label="Sponsoru @inodentry en GitHub ">GitHub-Sponsoroj | Ida Iyes</a>

Via oferdonaĵo helpas labori pri tia libere disponebla enhavo. Dankon! ❤️

## Subtenu Bevy

<a class="github-button" href="https://github.com/sponsors/cart" data-icon="octicon-heart" data-size="grande" aria-label="Sponsoru @cart sur GitHub ">GitHub-Sponsoroj | Bevy</a>

Se vi ŝatas na la Bevy Ludmotoro, vi devus konsideri oferdoni al la
oficiala projekto.

## Permesilo

Kopirajto © 2021-2022 Ida Iyes.

La tuta kodo de la libro estas provizita sub la
[Licenco MIT-0](https://github.com/bevy-cheatbook/mit-0).
Laŭ via elekto, vi ankaŭ povas uzi ĝin laŭ la regula MIT-permesilo.

La teksto de la libro estas provizita sub la
[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).

Escepto: Se uzata por la celo de kontribuo al la "Oficiala Bevy
Projekto", la tuta enhavo de la libro povas esti uzata sub la [MIT-0
Licenco](https://github.com/bevy-cheatbook/mit-0).

"Oficiala Bevy Projekto" estas difinita kiel:
 - Ajnaj dosieroj enhavitaj en la Git-deponejo estas gastigita ĉe [https://github.com/bevyengine/bevy](https://github.com/bevyengine/bevy)
 - Ajnaj dosieroj enhavitaj en la Git-deponejo estas gastigita ĉe [https://github.com/bevyengine/bevy-website](https://github.com/bevyengine/bevy-website)
 - Io ajn publike videbla en la retejo [bevyengine.org](https://bevyengine.org)

## Kontribuoj

Disvolviĝo de ĉi tiu libro estas gastigita en [GitHub][project::cb].

Bonvolu registri GitHub-Problemojn por ajna malĝusta/konfuza/misgvida informo,
kaj ankaŭ sugestojn pri nova enhavo, kiun vi ŝatus aldoniĝi al la libro.

Kontribuoj estas akceptitaj, kun kelkaj limigoj.

Vd. la sekcion [Kontribuo][cb::contributing] por ĉiuj detaloj.

## Averto pri Stabileco

Bevy estas ankoraŭ tre nova kaj eksperimenta ludmotoro! Ĝi nur estis
publika ekde aŭgusto 2020!

Dum plibonigoj okazas kun nekredebla ritmo, kaj disvolviĝo
estas aktiva, Bevy simple ankoraŭ ne havis la tempon maturiĝi.

*Ne ekzistas garantioj de la stabilecщ kaj rompiĝaj ŝanĝoj ofte okazas!*

Kutime, ne estas malfacile adaptiĝi al ŝanĝoj kun novaj eldonoj (aŭ eĉ spuri la ĉefa git-disvolva branĉo), sed vi estis avertita!
