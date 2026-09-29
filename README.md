# Statische VoyageStylo-Projektseite

Dieses Verzeichnis ist als **eigenständiger GitHub-Pages-Inhalt** gedacht. Es enthält nur eine Projektbeschreibung und Styles; keine OCR-Texte, Metadaten, Analyseergebnisse oder lokalen App-Skripte. Die Projektseite bietet keine interaktive Analyse. Diese benötigt den lokalen Python-Server und das lokale Korpus.

## Als separate GitHub-Pages-Site veröffentlichen

Die Seiteninhalte müssen in ein **eigenes Repository** kopiert werden, damit andere Dateien des VoyageStylo-Projekts nicht versehentlich mitveröffentlicht werden.

1. Erstelle unter deinem GitHub-Konto ein öffentliches Repository, zum Beispiel `reiseberichte-18-jahrhundert`.
2. Lade `index.html` und `styles.css` in den Repository-Stamm hoch.
3. Wähle unter **Settings → Pages** als Quelle **Deploy from a branch**, dann `main` und `/(root)`.
4. GitHub Pages baut und veröffentlicht die statische Seite anschliessend automatisch.

Bei Repositoryname `reiseberichte-18-jahrhundert` lautet die erwartete Adresse:

`https://marcel1911-p.github.io/reiseberichte-18-jahrhundert/`

## Datenschutz und Projektgrenzen

Veröffentliche nicht das vollständige VoyageStylo-Projekt als öffentliches Repository, wenn die darin enthaltenen OCR-Korpusdateien nicht ausdrücklich zur Weitergabe freigegeben sind. Der Quellenmanifest-Eintrag und die Projektunterlagen klären die Rechte nicht für alle Texte. Diese statische Seite macht keine Korpusdateien verfügbar und zeigt keine erfundenen Messergebnisse.

GitHub Pages führt weder den lokalen Python-Server aus noch stellt es die interaktive Analyse-API bereit. Die vollständige App bleibt lokal ausführbar; Details stehen in der Projekt-README.
