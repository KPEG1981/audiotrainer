CHINESE DRIVE TRAINER – PROTOTYP 1

1. Erzeuge mit Anki_Chinesisch_Autotraining.py aus deiner CSV die Audios.
   Die Dateien liegen danach in autotraining/media.
2. Veröffentliche die drei Dateien index.html, sw.js und manifest.webmanifest
   über einen HTTPS-Webhost (z.B. GitHub Pages). Das Öffnen der HTML-Datei
   direkt auf dem iPhone ist für die Offline-Speicherung nicht geeignet.
3. Öffne die HTTPS-Adresse auf dem iPhone in Safari und füge sie über
   Teilen > Zum Home-Bildschirm hinzu.
4. Importiere deine CSV und wähle alle MP3-Dateien aus autotraining/media.
   Zum Übertragen kannst du die MP3-Dateien vorher in der Dateien-App ablegen.
5. Einmal Start drücken. Der Player mischt alle Sätze pro Durchlauf neu.

CSV: Deutsch;Hanzi;Pinyin – UTF-8, mit oder ohne Kopfzeile.

WICHTIG:
- Die MP3-Dateinamen werden nach dem SHA256-Hash aus Hanzi und Deutsch
  abgeglichen; deshalb muss die CSV exakt zu den erzeugten MP3 passen.
- Daten bleiben lokal im Browser (IndexedDB), solange Safari sie nicht löscht.
- iOS kann Wiedergabe unterbrechen, wenn Safari in den Hintergrund wechselt.
- Ein aktiver Bildschirm und laufendes Safari/PWA-Fenster werden vorausgesetzt.
- Diese erste Version hat noch keinen echten Resume mitten im Satz.
- Bitte während der Fahrt keine Bedienelemente benutzen.
