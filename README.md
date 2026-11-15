# Cádiz-Rallye

Interaktive Stadtrallye für Cádiz mit zwei Altersstufen, Halbtag und Ganztag, Punkten und einem gemeinsamen Teamcode. Dazu eine Zeitreise zu den Völkern von Cádiz (Phönizier bis Spanier) als Vorbereitung.

- **Ältere Stufe:** 10 Jahre, 5./6. Klasse
- **Jüngere Stufe:** 7 Jahre, 2. Klasse

Die Namen der beiden Kinder trägt man auf der Startseite ein. Sie werden nur auf dem jeweiligen Handy gespeichert.

## Dateien

- `index.html`: die Rallye. Jedes Kind öffnet sie auf dem eigenen Handy, wählt den Namen und den Tag.
- `zeitreise.html`: Überblick über Phönizier, Karthager, Römer, Westgoten, Mauren und Spanier, je in einer Version für beide Stufen.
- `Voelker_in_Cadiz_A4.pdf`: Info- und Malblätter zu den Völkern in Cádiz (Phönizier, Karthager, Griechen, Römer, Westgoten, Wikinger, Mauren, Normannen, Hanseaten, Spanier) zum Ausdrucken, je Volk eine Seite mit Schiff und eine mit Figur.

Beides sind einzelne HTML-Dateien ohne Server. Der Spielstand liegt im Browser des jeweiligen Handys. Die Schriften kommen von Google Fonts, ohne Netz greift eine Standardschrift. Auf GitHub Pages teilen sich beide Seiten die eingetragenen Namen.

## Auf GitHub Pages veröffentlichen

1. Repository öffnen, Settings, Pages.
2. Unter "Build and deployment" die Quelle "Deploy from a branch" wählen, Branch `main`, Ordner `/ (root)`.
3. Nach einer Minute ist die Rallye unter `https://<name>.github.io/<repo>/` erreichbar, die Zeitreise unter `.../zeitreise.html`.

Hinweis: Pages braucht bei einem kostenlosen Konto ein öffentliches Repository.

## Anpassen

In `index.html` stehen die Stationen und Aufgaben als Liste (`DATA`) im Skript. Jede Aufgabe hat ein Feld `who`: `n` für die ältere Stufe, `h` für die jüngere Stufe, `nh` für beide. Die Beschriftung der Stufen steht weiter oben in `PL`.

Aufgabentypen: `quiz`, `riddle`, `num` (Rechnen oder Schätzen), `free` (Zählen oder Text), `photo`, `challenge`.

Geplant: die Altersstufen selbst einstellbar machen.

Alle Fakten sind gerundet und stammen aus allgemeinem Hintergrundwissen. Vor dem Einsatz bitte prüfen, vor allem Jahreszahlen, Öffnungszeiten und Adressen.
