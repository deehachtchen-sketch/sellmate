# SellMate – erster PWA-Prototyp

## Enthalten
- `index.html`: responsive Mobile-First-App
- `manifest.webmanifest`: PWA-Grundkonfiguration
- `sw.js`: einfacher Offline-Shell-Cache

## Lokal testen
Öffne `index.html` im Browser. Für PWA-Installation und Service Worker muss die App über HTTPS oder `localhost` bereitgestellt werden.

## Bereitstellung
Die Dateien können in ein GitHub-Repository gelegt und über GitHub Pages veröffentlicht werden. Danach die HTTPS-Adresse auf Android in Chrome öffnen und „App installieren“ bzw. „Zum Startbildschirm hinzufügen“ auswählen.

## Aktueller Funktionsumfang
- Artikel manuell erfassen
- Mehrere Fotos pro Artikel auswählen/aufnehmen
- Persönlichen oder gemeinsamen Bestand markieren
- Eigentümer, Startpreis und Mindestpreis erfassen
- Artikelbestand durchsuchen und filtern
- Verkauf mit Verkaufspreis und Kosten dokumentieren
- Erlöse und Verkaufsübersicht anzeigen
- JSON-Export als Datensicherung

## Noch nicht verbunden
Dieser Prototyp hat noch keine echte Cloud-Datenbank, Benutzerkonten, Gruppencodes, KI-Bilderkennung, automatische Marktpreisrecherche, Push-Nachrichten oder Kleinanzeigen-Anbindung. Die Daten werden lokal im Browser (`localStorage`) gespeichert. Bitte vorerst keine sensiblen Daten eingeben und regelmäßig exportieren.

## Nächster Entwicklungsschritt
Supabase-Projekt anlegen, Auth mit Magic Link konfigurieren, Tabellen und Row Level Security für persönliche und gemeinsame Bestände einrichten, danach den Frontend-Prototyp mit der Cloud verbinden.
