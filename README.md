# Moo Schmiede – RedM-Verwaltung

Hier wird die Moo-Schmiede-Webseite für GitHub Pages veröffentlicht.

## Website hochladen

1. Die Datei `Moo-Schmiede-GITHUB-PAGES-ONLINE.zip` **lokal entpacken**.
2. In diesem Repository **Add file → Upload files** auswählen.
3. **Die Dateien aus der ZIP**, insbesondere `index.html`, `app.js`, `cloud.mjs`, `engine.mjs`, `config.js`, `style.css`, `office.css`, `seed.json` und `whisper-logo.png`, **direkt ins Hauptverzeichnis** hochladen (kein Unterordner).
4. `Settings → Pages → Deploy from a branch → main → /(root) → Save` einstellen.
5. URL: https://kevdre96.github.io/moo-schmiede/

**Sicherheit:** Keine privaten SQL-, Excel- oder JSON-Importe auf GitHub hochladen. In der separaten Supabase-Datenbank muss erst das Moo-Schema mit RLS und Admin-Rechten eingerichtet werden, bevor Login und gemeinsame Speicherung funktionieren. Das bestehende Whisper-Projekt bleibt unabhängig davon.
