# Seenblick Angeln Schweiz – PWA

Diese Web-App kann auf dem iPhone über Safari zum Home-Bildschirm hinzugefügt werden. Die Dateien müssen zuerst über HTTPS gehostet werden.

## Funktionen
- Ausgewählte Schweizer Seen und Flüsse
- Suche nach Gewässer, Kanton und Fischart
- Karte, Favoriten und Gewässerdetails
- Live-Wetter via Open-Meteo: Lufttemperatur, gefühlte Temperatur, Wind, Böen, Windrichtung, Luftdruck, Luftfeuchte, Niederschlag und 6-Stunden-Ausblick
- Lokales Fangbuch mit optionalem Foto, Länge, Gewicht, Köder und Notizen
- Keine Standortfreigabe
- Wassertemperatur wird nicht erfunden; verlässliche Live-Daten sind noch nicht integriert

## Auf dem iPhone installieren
1. Erstelle ein GitHub-Repository (z. B. `seenblick-angeln`).
2. Lade `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png` und `icon-512.png` in den Hauptordner hoch.
3. Öffne die Repository-Einstellungen → Pages und aktiviere Veröffentlichung vom `main`-Branch und Root-Verzeichnis.
4. Öffne die erzeugte HTTPS-Adresse in Safari auf dem iPhone.
5. Tippe auf Teilen → Zum Home-Bildschirm; falls angeboten, aktiviere „Als Web-App öffnen“ → Hinzufügen.

## Hinweise
- Dieses ZIP ist ein Projektpaket, noch keine veröffentlichte Website.
- Wetter und Karte benötigen Internet.
- Fangbuch und Favoriten werden lokal im Browser gespeichert. Löschen der Website-Daten kann sie entfernen; Export/Backup ist noch nicht eingebaut.
- Es sind ausgewählte Gewässer, nicht alle Schweizer Gewässer. Koordinaten sind repräsentative Punkte, keine geprüften Angelplätze.
- Fischarten und Wetterhinweise sind Orientierung, keine amtlichen Bestandsdaten oder Fanggarantie. Vor dem Angeln Vorschriften, Schonzeiten, Mindestmasse, Bewilligungen und Schutzgebiete prüfen.
