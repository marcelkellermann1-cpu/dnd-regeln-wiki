---
tags: [DnD/Mordenkainen, Arbeitsanweisung]
typ: Übersetzungsauftrag
stand: 2026-06-29
---

# Mordenkainen Presents: Monsters of the Multiverse – Rohtext zur Übersetzung

Englischer Originaltext aus `mordenkainen_monsters_of_the_multiverse_-_Jeremy_crawford.pdf` (PDF-Extraktion, daher gelegentlich OCR-Artefakte wie verschobene Zeilenumbrüche oder „Ill" statt „11" — sinngemäß lesen, nicht 1:1 transkribieren).

**Aufgabe:** Jeden Teil übersetzen und als eigene `.md`-Datei mit Obsidian-Frontmatter ablegen — **eine Datei pro Spezies bzw. pro Monster**, nicht pro Textblock.

## Kapitel 1 – Spezies (3 Teile)
Zielordner: `Mordenkainen/01_Spezies/`

31 Spezies, alphabetisch: Aarakocra, Aasimar, Bugbear, Centaur, Changeling, Deep Gnome, Duergar, Eladrin, Fairy, Firbolg, Genasi (Air/Earth/Fire/Water — eine Datei mit 4 Varianten oder 4 einzelne, wie bei den Drachenblütigen in `Fizban/`), Githyanki, Githzerai, Goblin, Goliath, Harengon, Hobgoblin, Kenku, Kobold, Lizardfolk, Minotaur, Orc, Satyr, Sea Elf, Shadar-kai, Shifter, Tabaxi, Tortle, Triton, Yuan-ti.

Jede Spezies hat: Kurzbeschreibung (Lore), dann „**Traits**"-Abschnitt mit Creature Type, Size, Speed und 2-4 weiteren Eigenschaften (z. B. Darkvision, Fey Ancestry usw.) — analog zur Struktur, wie sie bereits in `D&D Spielerhandbuch 2024/01_Charakter/Spezies/` für die PHB-Spezies verwendet wird. Bitte gleiches Schema nutzen.

## Kapitel 2 – Bestiarium (24 Teile)
Zielordner: `Mordenkainen/02_Bestiarium/`

Über 250 Statblocks. Bitte **ein Statblock = eine Datei**, gleiches Schema wie die bestehenden Statblocks in `Ravenloft/` oder `Xantar/` (Frontmatter mit Herausforderungsgrad, Größe, Typ; Tabelle mit AC/HP/Speed/Attributen; Eigenschaften; Aktionen).

Bekannte Namen zur Orientierung (Auszug aus dem Inhaltsverzeichnis, nicht abschließend): Abishai (Black/Blue/Green/Red/White), Archdruid, Astral Dreadnought, Babau, Bael, Demogorgon, Drow (mehrere Varianten), Duergar (mehrere Varianten), Eladrin (Autumn/Spring/Summer/Winter), Frost/Fire/Cloud/Storm Giant (besondere Varianten), Ki-rin, Kobold (mehrere Varianten), Oblex, Ogre (mehrere Varianten), Orcus, Sword Wraith, Troll (Dire/Rot/Spirit/Venom), Vampiric Mist, Wizard (Apprentice/Abjurer/Conjurer/.../Transmuter — pro Schule eine Datei), Yuan-ti (mehrere Varianten), Zariel, Zuggtmoy u. v. m.

## Frontmatter-Vorlage

**Spezies:**
```yaml
---
tags: [DnD/Mordenkainen, Spezies]
typ: Regelseite
quelle: "Mordenkainen Presents: Monsters of the Multiverse"
stand: 2026-06-29
---
```

**Statblock:**
```yaml
---
tags: [DnD/Mordenkainen, Statblock]
typ: Statblock
quelle: "Mordenkainen Presents: Monsters of the Multiverse"
stand: 2026-06-29
---
```

## Wichtig
- Deutsche Fachbegriffe wie in den anderen Büchern verwenden (siehe `Xantar/`, `D&D Spielerhandbuch 2024/`, `Ravenloft/` für etablierte Übersetzungen von Begriffen wie *Trefferpunkte*, *Herausforderungsgrad*, *Rettungswurf* etc.).
- Verlinkung (`[[...]]`) wo naheliegend ergänzen, muss aber nicht perfekt sein — Claude prüft danach alle Links.
- Fertige Dateien einfach in den Zielordner schreiben.
