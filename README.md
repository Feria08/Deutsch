# Deutsch

Statische, interaktive Begleitseiten für den Deutschunterricht. Die veröffentlichte Übersichtsseite liegt unter:

https://weltraumcowboy67.github.io/Deutsch-besser/

## Enthaltene Unterrichtsreihe

### Expressionistische Großstadtlyrik (Deutsch 10)

Kurs-Guide mit Reihenplan, Epochenwissen, Kunst, Analyse-Handwerkszeug, Übungen, Quiz, Kratzkarten, Schreibwerkstatt und Klassenarbeits-Checkliste:

https://weltraumcowboy67.github.io/Deutsch-besser/expressionistische-grossstadtlyrik/

## Technik

- HTML, CSS und Vanilla JavaScript
- keine Build-Schritte und keine JavaScript-Abhängigkeiten
- lokale Speicherung von Entwürfen und Lernständen über localStorage
- statische Bilddateien im jeweiligen assets-Ordner
- geeignet für GitHub Pages

## Lokal starten

Im Projektordner:

    python3 -m http.server 4327 --bind 127.0.0.1

Danach http://127.0.0.1:4327/ im Browser öffnen. Der Port 4327 kann bei Bedarf durch einen freien Port ersetzt werden.

## GitHub Pages

Für die Veröffentlichung sind keine Anpassungen nötig. In den Repository-Einstellungen unter **Pages** als Quelle den Branch main und den Ordner / (root) wählen. Nach einem Push veröffentlicht GitHub die statischen Dateien direkt.

## Wichtige Dateien

- index.html: Übersichtsseite aller Unterrichtsreihen
- favicon.svg: gemeinsames Seitensymbol
- expressionistische-grossstadtlyrik/index.html: vollständige interaktive Unterrichtsseite
- expressionistische-grossstadtlyrik/assets/: lokal eingebundene, gemeinfreie Kunstabbildungen

## Datenschutz und Grenzen

- Die Seite besitzt kein Backend und überträgt keine eingegebenen Texte.
- Entwürfe, Quizantworten und Checklisten bleiben im jeweiligen Browser und können im Footer gelöscht werden.
- Schriftarten werden von Google Fonts geladen. Ohne Internet werden passende lokale Ersatzschriften verwendet.
- Externe Video- und Quellenlinks öffnen Seiten anderer Anbieter.

Weitere Unterrichtsreihen erhalten jeweils einen eigenen Unterordner und werden in index.html verlinkt.
