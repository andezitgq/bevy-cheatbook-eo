# Summary

[Enkonduko](./introduction.md)
[Superrigardo de Ĉapitroj](./overview.md)

---

[Ĉu komencanto en Bevy? Tute Gvidita Instrukcio!](./tutorial.md)

---

[Listo de Bevy Enkonstruitaĵoj](./builtins.md)

---

- [Konsiloj pri Bevy Instalado](./setup.md)
  - [Komencante](./setup/getting-started.md)
  - [Uzado de bleeding-edge Bevy (ĉefa)](./setup/bevy-git.md)
  - [Tekstredaktilo / Integra Ellaborad-Medio](./setup/editor.md)
  - [Ellaboriloj kaj Redaktiloj por Bevy](./setup/bevy-tools.md)
  - [Ekosistemo de Komunumaj Kromaĵoj](./setup/unofficial-plugins.md)
  - [Agordado de Bevy (trajtoj, modulareco)](./setup/bevy-config.md)

- [Ĝeneralaj Kaptiloj](./pitfalls.md)
  - [Strangaj kompilad-eraroj el Bevy aŭ dependaĵoj](./pitfalls/build-errors.md)
  - [Malrapida Plenumeco](./pitfalls/performance.md)
  - [Eraro aldonante funkcion kiel sistemo](./pitfalls/into-system.md)
  - [UI ne bildiĝas](./pitfalls/ui-camera.md)
  - [2D-objektoj ne bildiĝas](./pitfalls/2d-camera-z.md)
  - [3D-objektoj ne bildiĝas](./pitfalls/3d-not-rendering.md)
  - [Pruntepreni plurajn kampojn de struct](./pitfalls/split-borrows.md)
  - [Interrompema moviĝo/animacio](./pitfalls/time.md)
  - [UI aranĝo estas inversigita](./pitfalls/ui-y-up.md)
  - [Teksturoj/Bildoj estas renversitaj](./pitfalls/uv-coordinates.md)

- [Kerno de Bevy Ludmotoro](./features.md)
  - [Koordinata Sistemo](./features/coords.md)
  - [Transformoj](./features/transforms.md)
  - [Tempo kaj Tempigiloj](./features/time.md)
  - [Parento-Ido Hierarĥioj](./features/parent-child.md)
  - [Difinita Tempopaŝo](./features/fixed-timestep.md)
  - [Aŭdio](./features/audio.md)

- [Administrado de Valoraĵoj](./assets.md)
  - [Priskribiloj (Handles)](./assets/handles.md)
  - [Elŝuti Valoraĵojn el Dosieroj](./assets/assetserver.md)
  - [Atingo al la Valoraĵ-datumo](./assets/data.md)
  - [Reagi al Ŝanĝoj kun Valoraĵ-eventoj](./assets/assetevent.md)
  - [Observi Elŝut-progreson](./assets/ready.md)
  - [Tuj-Reŝargo de Valoraĵoj](./assets/hot-reload.md)

- [Eniga Priskribilo](./input.md)
  - [Klavaro](./input/keyboard.md)
  - [Muso](./input/mouse.md)
  - [Teksto / Simbolo](./input/char.md)
  - [Ludstirilo (Kontrolilo, Stirstango)](./input/gamepad.md)
  - [Tuŝekrano](./input/touch.md)
  - [Treni-k-faligi (Dosierojn)](./input/dnd.md)
  - [MIDI (Muzikilo)](./input/midi.md)

- [Administrado de Fenestroj](./window.md)
  - [[Nefinita] Fenestraj Ecoj](./window/props.md)
  - [Ŝanĝo la Fonkoloron](./window/clear-color.md)
  - [Kapti la Muskursoron](./window/mouse-grab.md)
  - [Difini la Fenestran Ikoneton](./window/icon.md)

- [Bevy 2D](./2d.md)
  - [[Nefinita] 2D Kamerao-instalado](./2d/camera.md)
  - [[Nefinita] Sprajtoj kaj Atlasoj](./2d/sprites.md)

- [Bevy 3D](./3d.md)
  - [[Nefinita] 3D Kamerao-instalado](./3d/camera.md)
  - [3D Modeloj kaj Scenejoj (GLTF)](./3d/gltf.md)

- [Bevy Programada Enkadraĵo (Framework)](./programming.md)
  - [Enkonduko al EKS](./programming/ecs-intro.md)
  - [Entoj kaj Komponantoj](./programming/ec.md)
  - [Risurcoj](./programming/res.md)
  - [Sistemoj](./programming/systems.md)
  - [Informpetoj](./programming/queries.md)
  - [Komandoj](./programming/commands.md)
  - [Eventoj](./programming/events.md)
  - [Aplikaĵa Konstruilo (fn main)](./programming/app-builder.md)
  - [Ĉesi la Aplikaĵon](./programming/quit.md)
  - [Lokaj Risurcoj](./programming/local.md)
  - [Kromaĵoj](./programming/plugins.md)
  - [Sistema Ordo de Plenumado](./programming/system-order.md)
  - [Sistemaj Aroj](./programming/system-sets.md)
  - [Detekto de Ŝanĝo](./programming/change-detection.md)
  - [Statoj](./programming/states.md)
  - [Lanĉaj Kriterioj](./programming/run-criteria.md)
  - [Titoloj](./programming/labels.md)
  - [Etapoj](./programming/stages.md)
  - [Detekto de Forigo](./programming/removal-detection.md)
  - [Parametraj Aroj](./programming/paramset.md)
  - [Sistema Ligado](./programming/system-chaining.md)
  - [Direkta Atingo al EKS-Mondo](./programming/world.md)
  - [Ekskluzivaj Sistemoj](./programming/exclusive.md)
  - [[Nefinita] Sub-Aplikaĵoj](./programming/sub-apps.md)
  - [Nesendaj Risurcoj](./programming/non-send.md)
  - [Kreado de Testoj por Sistemoj](./programming/system-tests.md)

- [Programadaj Ŝablonoj](./patterns.md)
  - [Generaj Sistemoj](./patterns/generic-systems.md)
  - [Komponanta Stokaĵo (Tabelo/SparseSet)](./patterns/component-storage.md)
  - [Permana Event-Malplenigo](./patterns/manual-event-clear.md)

- [[Nefinita] Bevy Bildiga (GPU) Enkadraĵo](./gpu.md)
  - [Superrigardo de Bildiga Arĥitekturo](./gpu/intro.md)

- [Bevy Kuirlibro](./cookbook.md)
  - [Montri Kadrofrekvencon in Terminalo](./cookbook/print-framerate.md)
  - [Konverti kursoron en mondajn koordinatojn](./cookbook/cursor2world.md)
  - [Propra Kamera-Projekcio](./cookbook/custom-projection.md)
  - [Panorama + Orbita Kamerao](./cookbook/pan-orbit-camera.md)
  - [Listo de Ĉiuj Risurcaj Tipoj](./cookbook/print-resources.md)

- [Bevy en Diversaj Platformoj](./platforms.md)
  - [Linuks-Labortablo](./platforms/linux.md)
  - [MakOS-Labortablo](./platforms/macos.md)
  - [Vindoz-Labortablo](./platforms/windows.md)
  - [Transkompilado](./setup/cross.md)
    - [El Linukso al Vindozo](./setup/cross/linux-windows.md)
  - [Retumilo (WebAssembly)](./platforms/wasm.md)
    - [Panikaj Mesaĝoj](./platforms/wasm/panic-console.md)
    - [Grandeca Optimumigo](./platforms/wasm/size-opt.md)
    - [Gastigado en GitHub-Pages](./platforms/wasm/gh-pages.md)

---

[Aŭtoroj](./credits.md)

---

[Kontakti kun la aŭtoro](./contact.md)

---

[Kontribui al Bevy](./contributing-bevy.md)
[Kontribui al la Origina Libro](./contributing.md)
