# Kontribuado

{{#include ./include/links.md}}

Estu ĝentila. Se vi bezonas kondutkodon, rigardu tiun de Bevy.

Se vi havas sugestojn por la libro, kiel ideojn por nova enhavo, aŭ se vi rimarkas ion malĝustan aŭ misgvida, bonvolu registri problemojn en la [deponejo de GitHub][project::cb]!

## Kod-kontribuado

Se vi simple volas kontribui kodekzemplojn al la libro, ne timi fari memreklamon! Mi povas zorgi pri skribo de la libroteksto / paĝo, en kiu via kodo
estos montrata.

### Kuirlibraj Ekzemploj

La kodo por kuirlibraj ekzemploj devas esti provizita kiel plena, lanĉebla ekzempla dosiero en `src/code/examples` vojo. La libropaĝo nur montros la konvenajn partojn de la kodo sen malnecesa kaldrono.

Always use [mdbook anchor syntax][mdbook::anchor-syntax], not line numbers,
to denote the parts of the code to be shown on the page.

Ĉiam uzu [mdbook ankro-sintakson][mdbook::anchor-syntax]

### Aŭtor-mencioj

Se vi kontribuos ekzemplon por [Originala Kuirlibro](https://bevy-cheatbook.github.io/cookbook.html), la aŭtoro mencios vin en la libro per via GitHub-uzantnomo kaj la ligilo.

## Kontribuado al Libroteksto

La aŭtoro ne kunigas direkte la librotekston, verkitan de aliaj homoj. Ĉi tio estas ĉar mi deziras konservi certan redaktistan stilon.

Se vi dezirus verki novan enhavon por la libro, ne timu fari reklamon kun la inkludita enhavo, sed notu, ke ĝi verŝajne ne estos konservita samkiel vi skribis ĝin.

## Licencado

Por eviti komplikaĵojn kun kopirajto kaj licencado, vi konsentas provizi ajnajn kontribuojn, kiujn vi faras al la projekto per la [MIT-0 Malatribua Permesilo](https://github.com/bevy-cheatbook/mit-0).

Atentu, ke ĝi rajtigas ne konservi kopirajton de via laboro dum relicencado.

Kiel estis priskribita antaŭe, la reala publikigita enhavo en la libro estas propra derivita laboro de la libraŭtoro, bazita sur viaj kontribuoj. Vd. la [licencon](./introduction.md#permesilo).

## Bevy versio

Enhavo, verkita por la nuna eldono de Bevy, estas akceptita por la `main` branĉo de la originala libro.

Enhavo, verkita por novaj disvolvaĵoj en la ĉefa branĉo de Bevy, estas akceptita por la `next` branĉo de la originala libro, en preparo por la venonta Bevy-eldono.

## Stil-gvidaĵo

- Celu simplecon kaj minimumismon. Ne skribu pri maloportunaj kaj senrilataj aferoj.
 
- Perfekteco estas atingita ne kiam estas nenio por aldoni, sed kiam estas nenio por forigi.

- Ne forgesu indiki potencialajn erarojn kaj aliajn gravajn praktikajn konsiderojn.

- Penu uzi la plej ofte uzantajn terminologion kaj ĉefvortojn por igi aferojn facile troveblaj. Ne elpensu novan/kroman terminologion mem.
it instead.

- Evitu ripetadon de informoj, trovitaj aliloke en la libro, anstataŭe provizu ligon al ĝi.

### Koda stilo

Evitu longajn liniojn de kodo por legebligi ĝin en malgrandaj ekranoj.

Uzu prudentan formatadon, kiu ne multe distingiĝas de la ĝenerale akceptitaj konvencioj, uzataj de la Rustlingva komunumo. Sed ne estas necese uzi na `rustfmt`. Se devio de ĉi tiuj normoj permesas pli bone prezenti la kodon en la kunteksto de la libro, tiam tio estas preferinda.

### Teksta stilo

Farigu ĝin facila por legado:

- Estu lakona. Provu kovri ĉiujn gravajn informojn sen detalaj klarigoj.
- Preferu simplan lingvon kun mallongaj frazoj.
- Evitu informan troŝarĝon:
  - Dividu aferojn en mallongajn alineojn.
  - Evitu diskuti multajn (eĉ rilatajn) temojn samtempe.
  - Diskutu progresintan uzadon aparte de bazaĵoj.

