# Schnuppertagebuch

Eine eigenständige, selbstständige Webseite (eine einzige `index.html`-Datei) für das Schnuppertagebuch. Alle Einträge werden lokal im Browser der jeweiligen Person gespeichert (localStorage) – es ist kein Server und keine Datenbank nötig.

## Auf GitHub Pages veröffentlichen

1. Erstelle auf [github.com](https://github.com) ein neues **Repository** (z. B. `schnuppertagebuch`). Öffentlich oder privat spielt für die Funktion keine Rolle – öffentlich ist für GitHub Pages im Gratis-Plan nötig, ausser du hast GitHub Pro.
2. Lade die Datei **`index.html`** aus diesem Ordner direkt ins Hauptverzeichnis (root) des Repositories hoch ("Add file" → "Upload files").
3. Gehe im Repository auf **Settings → Pages**.
4. Wähle bei "Source" den Branch **`main`** und den Ordner **`/ (root)`**, dann **Save**.
5. Nach ein bis zwei Minuten ist die Seite erreichbar unter:
   `https://<dein-github-name>.github.io/<repo-name>/`
6. Diesen Link kannst du an die Schüler verteilen (z. B. als QR-Code).

## Wichtig zu wissen

- Jede Person, die den Link öffnet, bekommt automatisch ihr eigenes, privates Tagebuch – solange sie dasselbe Gerät/denselben Browser weiterverwendet.
- Über die Knöpfe **"Drucken / als PDF sichern"**, **"Sichern als Datei"** und **"Einreichen"** können die Einträge jederzeit gesichert bzw. bei der Lehrperson eingereicht werden.
- Update später einfach die `index.html` im Repository, um Änderungen zu veröffentlichen (Bestehende Daten der Schüler bleiben davon unberührt, da sie lokal gespeichert sind).
