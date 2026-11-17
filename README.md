# International Perspectives on Inclusion and Exclusion

Interaktives Skript zum Seminar von Prof. Dr. Mehmet Kart, OTH Regensburg (WiSe 2026/27).

## Was wo liegt

```
index.qmd                Willkommensseite
part-1/                  Part I, Kapitel 1: Übersicht (01-00) und Unterkapitel 1.1–1.10
                         (1.4 = Key Terms mit aufklappbaren Begriffen)
part-2/ … part-7/        Teil II–VII, eine Seite je Kapitel (Kapitel 2–24)
02-theories.qmd          Theories and Concepts
03-learning-games.qmd    Learning Games (Memory, Fälle zuordnen)
04-learning-check.qmd    Learning Check
interactions/            die drei Lernspiele als HTML-Dateien
images/                  Abbildungen
fonts/                   Schrift Outfit (OTH), lokal eingebunden
include/                 Technik: passt die Höhe der Lernspiele an
_quarto.yml              Einstellungen (Titel, Navigation links, Fußzeile)
styles.scss              Layout im OTH-Design
docs/                    fertige Webseite (wird automatisch erzeugt, nicht von Hand ändern)
```

## Neue Seite hinzufügen

Neue `.qmd`-Datei anlegen (z. B. `part-1/01-11-....qmd`) und in `_quarto.yml` unter `sidebar: contents:` an der gewünschten Stelle eintragen.

## Webseite aktualisieren

1. `.qmd`-Datei in RStudio bearbeiten und speichern.
2. Im Reiter *Terminal*: `quarto render`
3. In GitHub Desktop: kurze Notiz eintragen, **Commit to main**, dann **Push origin**.

Nach ein bis zwei Minuten ist die Webseite aktualisiert (im Browser mit Strg+F5 neu laden).
