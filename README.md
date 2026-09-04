# Karteikarten Fachtierarzt Pferd
Dies ist der Link zu den Karteikarten: https://bgbhhhsd.github.io/Karteikarten/

Readme · MD
🐴 FTA-Karteikarten – Anleitung zur Aktualisierung

Diese Anleitung erklärt, wie du eine neue Version der Karteikarten-App in GitHub hochlädst, damit sie unter https://bgbhhhsd.github.io/Karteikarten/ abrufbar ist.

📋 Was du brauchst
Einen Browser (Chrome, Firefox, Safari …)
Die neue HTML-Datei (z. B. Karteikarten_Mobil_v22.html) auf deinem Computer
Deinen GitHub-Account (bgbhhhsd)
🚀 Schritt-für-Schritt: Neue Version hochladen
Schritt 1 – GitHub öffnen und einloggen
Gehe zu github.com und logge dich ein.
Klicke oben rechts auf dein Profilbild → Your repositories.
Klicke auf das Repository Karteikarten.
Schritt 2 – Datei hochladen
Du siehst die Dateien in deinem Repository. Klicke auf die Schaltfläche „Add file" (oben rechts im Dateibereich).
Wähle „Upload files" aus dem Dropdown.
Ziehe deine neue HTML-Datei (z. B. Karteikarten_Mobil_v22.html) in das Upload-Feld,
oder klicke auf „choose your files" und wähle sie aus.
Warte, bis der Upload abgeschlossen ist (grüner Haken erscheint).
Schritt 3 – Datei als Startseite festlegen (nur einmal nötig, danach überspringen)

Die Seite unter https://bgbhhhsd.github.io/Karteikarten/ zeigt immer die Datei namens index.html an.
Du hast zwei Möglichkeiten:

Option A – Datei direkt index.html nennen (empfohlen)

Benenne deine Datei vor dem Upload in index.html um (einfach im Windows-Explorer Rechtsklick → Umbenennen).
Beim Upload wirst du gefragt, ob du die bestehende index.html ersetzen möchtest → „Commit changes" bestätigen.

Option B – Versionsnamen behalten und per Hand verlinken (für Fortgeschrittene)

Falls du die Versionsbezeichnung behalten möchtest (z. B. Karteikarten_Mobil_v22.html):

Öffne die bereits vorhandene index.html im Repository per Klick darauf.
Klicke oben rechts auf das Stift-Symbol (✏️ „Edit this file").
Ändere im Code den Dateinamen auf die neue Version, z. B.:
html
   <meta http-equiv="refresh" content="0; url=Karteikarten_Mobil_v22.html">
Weiter mit Schritt 4.
Schritt 4 – Änderung speichern (Commit)
Scrolle auf der Upload-Seite nach unten zum Abschnitt „Commit changes".
Im ersten Textfeld steht automatisch ein Vorschlag (z. B. „Add files via upload") –
du kannst es so lassen oder etwas Eigenes schreiben, z. B. v22 hochgeladen.
Klicke auf den grünen Button „Commit changes".
Schritt 5 – Fertig! Seite aufrufen
Warte ca. 1–2 Minuten, bis GitHub die Seite neu baut.
Öffne dann: https://bgbhhhsd.github.io/Karteikarten/
Wenn die Seite noch die alte Version zeigt: Strg + Shift + R (Windows) oder Cmd + Shift + R (Mac) drücken, um den Browser-Cache zu leeren.
🔄 Kurzversion für spätere Updates (wenn du es schon kennst)
Repository öffnen → Add file → Upload files
Neue index.html hochladen (alte wird ersetzt)
Commit changes klicken
~2 Minuten warten → Seite aufrufen
❓ Häufige Probleme
Problem	Lösung
Seite zeigt noch alte Version	Strg+Shift+R (Hard Refresh) im Browser
Upload-Button ist ausgegraut	Seite neu laden und nochmal versuchen
404-Fehler nach Upload	Datei muss index.html heißen ODER GitHub Pages Einstellungen prüfen (Settings → Pages → Source: main branch)
Änderungen sichtbar, aber Karten laden nicht	HTML-Datei ist beschädigt – vorherige Version wiederherstellen
⚙️ GitHub Pages Einstellungen prüfen (nur falls nötig)

Falls die Seite gar nicht erreichbar ist:

Im Repository: Settings (oben in der Navigationsleiste)
Links im Menü: Pages
Unter „Source": muss „Deploy from a branch" ausgewählt sein
Branch: main (oder master), Ordner: / (root)
Speichern → ca. 2–5 Minuten warten

Zuletzt aktualisiert: September 2026
