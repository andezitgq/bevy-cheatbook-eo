# Komencante

{{#include ../include/links.md}}

Ĉi tiu paĝo kovras la bazan agordadon, bezonan por Bevy-ellaborado.

---

Plejparte, Bevy estas sama, kiel iu ajn alia Rust-biblioteko. Vi bezonas
instali na Rust kaj agordi vian ellaborad-medion. Vi povas instali Rust, uzante [Rustup][rustup]. Vidu
[La oficialan agordan paĝon de Rust][rust::getting-started].

En Linukso, vi bezonas la ellaborad-dosierojn por kelkaj sistemaj bibliotekoj. Vd. la
[oficialan Bevy Linuks-dependaĵan paĝon][bevy::linux-dependencies].

Ankaŭ vd. la [Agordan paĝon en la oficiala Bevy Libro][bevy::getting-started] kaj la [oficialan Bevy Readme (Leguminaĵon)][bevy::getting-started]

{{#include ../include/gpu-driver-requirements.md}}

## Kreado de Nova Projekto

Vi povas simple krei novan Rust-projekton aŭ pre via Redaktilo, aŭ per la Terminalo:

```sh
cargo new --bin mia_ludo
```

(ĝi kreas projekton, nomita `mia_ludo`)

La `Cargo.toml` dosiero enhavas ĉiu agordaĵon de via projekto. Aldonu la lastan version de `bevy` kiel dependaĵo. Via dosiero nun aspektas kiel ĉi tio:

```toml
[package]
name = "mia_ludo"
version = "0.1.0"
edition = "2021"

[dependencies]
bevy = "0.7"
```

La `src/main.rs` estas via ĉefa	fontkoda dosiero. Ĉi tie vi komencas skribi vian Rust-kodon. Por minimuma Bevy-aplikaĵo vi bezonas almenaŭ sekvantan:

```rust,no_run,noplayground
{{#include ../code/examples/minimal.rs}}
```

Vi povas nun kompili kaj lanĉi vian projekton. Unufoje daŭros iom da tempo, ĉar vi devas kompili tutan Bevy-motoron kaj dependaĵojn. Sekvaj kompiladoj devas esti pli rapidaj. Vi povas ankaŭ fari tion el via Redaktilo aŭ Terminalo:

```sh
cargo run
```

## Plia Agordado

Vi verŝajne renkontos kun maluzebla malrapida plenumeco en defaŭltaj neoptimigitaj Rust-konstruaĵoj. [Vd. kiel ripari ĉi tion][pitfall::perf]

Ankaŭ, ripeta rekompila rapideco estas grava por teni vin produktiva,
tial vi ne devas atendi longe, ke la Rust-kompililo rekompilu vian
projekton ĉiufoje, kiam vi deziras testi vian ludon. [Bevy komencant-paĝo][bevy::getting-started] havas konsilon pri kiel plirapidigi kompiltempon.

Ankaŭ vd. [Ellaboriloj kaj Redaktiloj][cb::tools] paĝon por sugestoj pri pliaj eksteraj ellaboriloj, kiuj povus esti utilaj.

## Kio estas plu?

Vidu [gviditan instrukcion][chapter::tutorial] de ĉi tiu libro kaj [oficialajn ekzemplojn][bevy::examples] de Bevy.

Vizitu la [Bevy Valoraĵ-retejon][bevy::assets] por trovi aliajn lernilojn kaj lern-risurcojn de la komunumo, ankaŭ kromaĵojn por uzi en via projekto.

Aliĝu al la komunumo en [Diskordo][bevy::discord] por babili kun ni!

## Ĉu vi havas problemojn?

Se io ne funkcias, vizitu [Ĝeneralajn Kaptilojn][chapter::pitfalls] por vidi, ĉu la libro havas ion por helpi vin. Ĝi dokumentas solvadojn al kelkaj el la plej oftaj problemoj, kiujn renkontis membroj de la Bevy-komunumo.

Se vi bezonas helpon, uzu [GitHub-diskutojn][bevy::ghdiscussions] aŭ vizitu la babilejon kaj demandi por helpo en [Diskordo][bevy::discord].
