# NotenPilot Schweiz – GitHub Pages

Diese Version kann ohne Build-Schritt als statische Website auf GitHub Pages veröffentlicht werden.

## Veröffentlichung

1. Erstelle auf GitHub ein neues Repository, zum Beispiel `notenpilot`.
2. Lade **den gesamten Inhalt dieses Ordners** in die oberste Ebene des Repositorys hoch. `index.html` muss direkt im Hauptordner liegen.
3. Öffne im Repository **Settings → Pages**.
4. Wähle unter **Build and deployment** die Quelle **Deploy from a branch**.
5. Wähle den Branch **main** und den Ordner **/(root)**, dann **Save**.
6. GitHub zeigt danach die öffentliche Adresse an, meistens `https://BENUTZERNAME.github.io/notenpilot/`.

## Enthalten

- `index.html` – komplette NotenPilot-App
- `manifest.webmanifest` und App-Symbole – Installation als Web-App
- `sw.js` – Offline-Zwischenspeicher nach dem ersten Besuch
- `.nojekyll` – verhindert unerwünschte Jekyll-Verarbeitung

## Wichtig zu Daten und Anmeldung

NotenPilot verwendet aktuell **keinen Server und keine Online-Datenbank**. Konten, Passwörter und Noten werden nur im lokalen Browser-Speicher des jeweiligen Geräts abgelegt. Deshalb:

- sind Daten nicht automatisch zwischen Geräten synchronisiert;
- sieht ein anderer Browser oder ein anderes Gerät die Konten nicht;
- sollte regelmässig die Export-/Sicherungsfunktion der App verwendet werden;
- ist diese lokale Anmeldung nicht für vertrauliche oder institutionelle Echtdaten gedacht.

Für echte Online-Konten und geräteübergreifende Synchronisation wäre später ein Backend nötig, zum Beispiel Supabase oder Firebase.
