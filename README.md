# Truppführer – Prüfungstraining (QS3)

Karteikarten, Prüfungssimulation und Übersicht (Markierungen, Bewertungen, Notizen)
für die theoretische Truppführer-Prüfung. Läuft als reine statische Webseite – kein Server, kein Build.

## Aufbau

```
index.html                  # die App (lädt die Fragen aus /questions)
questions/
  manifest.json             # Liste aller Themendateien (Reihenfolge)
  01-wasserfuehrende-armaturen.json
  02-fahrzeuge.json
  ...                       # eine Datei pro Thema
.nojekyll
README.md
```

Die Fragen stehen **NICHT** in der Webseite, sondern im Ordner `questions/`.
Bearbeitet wird ausschließlich über diese Dateien (nicht über die Webseite).

## Inhaltliche Grundlage
Die Fragen orientieren sich u. a. an
- NABK-Ausbildungsunterlage **Truppmannausbildung Teil 1** (Stand 21.01.2020)
- NLBK-Lernunterlage **Löscheinsatz (QS 1)** (Stand 09/2023) sowie der **FwDV 3**

## Fragen bearbeiten / hinzufügen / löschen

Jede Themendatei sieht so aus:

```json
{
  "topic": "Wasserführende Armaturen",
  "cards": [
    {
      "q": "Frage steht hier?",
      "a": "Antwort steht hier.",
      "l": "Wikipedia-Artikelname"
    }
  ]
}
```

- **Frage ändern:** Text bei `q` / `a` anpassen.
- **Frage hinzufügen:** einen neuen `{ "q": "...", "a": "...", "l": "..." }`-Block in die `cards`-Liste einfügen (Blöcke mit Komma trennen, der letzte ohne Komma).
- **Frage löschen:** den entsprechenden Block entfernen.
- `l` ist der **Nachlese-Link**: der genaue Titel eines deutschen Wikipedia-Artikels
  (z. B. `"Saugkorb"`). Die App baset daraus automatisch den Link
  `https://de.wikipedia.org/wiki/Saugkorb`. `l` darf auch leer (`""`) sein.

### Neues Thema hinzufügen
1. Neue Datei in `questions/` anlegen, z. B. `16-mein-thema.json` (gleicher Aufbau wie oben).
2. Den Dateinamen in `questions/manifest.json` in die Liste `topics` eintragen
   (die Reihenfolge dort bestimmt die Reihenfolge in der App).

> Wichtig: Es muss gültiges JSON bleiben – auf Kommas und Anführungszeichen achten.
> Tipp: Vor dem Hochladen kurz durch einen JSON-Prüfer jagen (z. B. jsonlint.com).

## Lokal testen
Doppelklick auf `index.html` reicht **nicht** (Browser blockiert das Laden der Dateien per `file://`).
Stattdessen im Projektordner einen kleinen Webserver starten:

```
python3 -m http.server
```

Dann im Browser `http://localhost:8000` öffnen.

## Auf GitHub Pages veröffentlichen
1. Alle Dateien (inkl. Ordner `questions/`) ins Repository hochladen.
2. Im Repo: **Settings → Pages**.
3. Bei **Source**: „Deploy from a branch“, Branch **main**, Ordner **/(root)**, **Save**.
4. Nach 1–2 Minuten ist die Seite erreichbar unter:
   `https://lorzmario.github.io/Truppf-hrerPr-fungstraining/`

Jede spätere Änderung an den Dateien aktualisiert die Seite automatisch.

## Speicherung von Markierungen/Bewertungen/Notizen
Diese werden lokal im Browser gespeichert (localStorage) – **pro Browser und pro Gerät**,
es wird nichts synchronisiert. Verlauf/Websitedaten löschen entfernt sie wieder.
