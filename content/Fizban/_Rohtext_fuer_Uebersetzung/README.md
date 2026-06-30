---
tags: [DnD/Fizban, Arbeitsanweisung]
typ: Übersetzungsauftrag
stand: 2026-06-28
---

# Fizban's Treasury of Dragons – Rohtext zur Übersetzung

Dieser Ordner enthält den **englischen Originaltext** aus `Fizban's_Treasury_of_Dragons.pdf` (bereits aus der PDF extrahiert, daher gelegentlich kleine OCR-Artefakte wie Zeilenumbruch-Fehler — bitte sinngemäß lesen, nicht 1:1 transkribieren).

**Aufgabe:** Jeden Teil ins Deutsche übersetzen und als eigene `.md`-Datei mit Obsidian-Frontmatter im Vault ablegen (siehe Vorlage unten). Keine Strukturentscheidungen nötig — einfach Inhalt sinnvoll in Abschnitte mit `##`-Überschriften gliedern, wie es der Originaltext vorgibt.

## Zielordner pro Kapitel

| Datei-Präfix | Inhalt | Zielordner im Vault |
|---|---|---|
| `Kapitel2_Drachenmagie_*` | Zauber, Magische Gegenstände, Hort-Gegenstände, Drachengaben | `Fizban/02_Drachenmagie/` |
| `Kapitel3_Drachen_im_Spiel_*` | Rollenspiel-Regeln, Drachenpersönlichkeit, Abenteuerideen | `Fizban/03_Drachen_im_Spiel/` |
| `Kapitel4_Horte_*` | Regeln für Drachenhorte, Hort-Tabellen | `Fizban/04_Horte/` |
| `Kapitel5_Draconomicon_*` | 20 Drachenarten alphabetisch (Amethyst bis Weiß) — bitte **pro Drachenart eine eigene Datei**, z. B. `Draconomicon_Amethystdrache.md` | `Fizban/05_Draconomicon/` |
| `Kapitel6_Bestiarium_*` | ~70 Statblocks (Drachen aller Altersstufen + Verwandte) — bitte **pro Kreatur eine eigene Datei**, gleiches Namensschema wie bestehende Statblocks im Vault | `Fizban/06_Bestiarium/` |

## Frontmatter-Vorlage

```yaml
---
tags: [DnD/Fizban, <Kategorie, z.B. Zauber/Drache/Statblock>]
typ: <Regelseite/Statblock/Lesetext>
quelle: "Fizban's Treasury of Dragons, Kapitel X"
stand: 2026-06-28
---
```

## Wichtig
- **Deutsche Fachbegriffe** wie in den anderen Büchern verwenden (Schaut in `Xantar/`, `Tashas/` oder `D&D Spielerhandbuch 2024/` nach, wie Begriffe wie *Trefferpunkte*, *Rettungswurf*, *Zauberplatz* etc. bereits übersetzt sind, statt neue Varianten zu erfinden).
- Verlinkung (`[[...]]`) zwischen den neuen Dateien und zu `Fizban/00_Masterplan.md` bitte ergänzen, wo es naheliegt — muss aber nicht vollständig/perfekt sein, das übernimmt Claude in der Nachbearbeitung.
- Wenn fertig: einfach in den Zielordner schreiben, Claude prüft danach alle Links.
