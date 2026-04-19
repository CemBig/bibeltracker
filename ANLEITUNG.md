# Bibeltracker – Anleitung zum Installieren auf dem iPhone

## Option A: Netlify Drop (kein Account nötig, 2 Minuten)

1. Gehe auf https://app.netlify.com/drop
2. Ziehe den **ganzen Ordner** `Bibelleseapp` in das Browserfenster
3. Netlify gibt dir eine URL wie `https://random-name-123.netlify.app`
4. Diese URL auf dem iPhone in Safari öffnen
5. Unten auf **"Teilen"** tippen → **"Zum Home-Bildschirm"** → Fertig!

## Option B: GitHub Pages (dauerhafter, kostenlos)

1. GitHub-Account anlegen auf github.com (falls noch nicht vorhanden)
2. Neues Repository erstellen: "bibeltracker"
3. Alle Dateien hochladen (oder via `git push`)
4. Im Repository: Settings → Pages → Source: main branch
5. URL: `https://DEINNAME.github.io/bibeltracker`
6. Auf iPhone in Safari öffnen → "Zum Home-Bildschirm"

## Nach der Installation auf dem iPhone

- Die App erscheint mit eigenem Icon auf dem Home-Bildschirm
- Funktioniert **offline** – keine Internetverbindung nötig
- Daten werden lokal im Browser gespeichert (localStorage)
- **Achtung:** Daten sind gerätespezifisch – Mac und iPhone haben getrennte Fortschritte

## Fortschritt zwischen Geräten synchronisieren?

Das ist möglich, würde aber einen kleinen Backend-Service benötigen.
Sprich mich an, wenn du das einrichten möchtest.
