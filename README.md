# TEALP - Thumbnail Editor Automator for Lets Plays

## Der Workflow von Thumbnails

1. Extrahieren der gewünschten Stelle im Video
2. Wenn erwünscht weitere Bilder aufsuchen
3. Bilder freistellen in Paint3D
4. Laden der freigestellten Bilder in Krita
5. Weitere Effekte einfügen
6. Speichern nach

## 🔍 Hauptprobleme

* Dateimanagement
    * Thumbnails müssen manuell herausgesucht werden. FileManager
    * Langsamer Transfer zwischen Programmen.
    * Kein direkter Zugriff auf bereits verwendete Daten.
    * Schlechte oder gar keine direkte Vorschau der Daten.
* Langes heraussuchen eines passenden Thumbnails
    * Es muss über VLC ein Thumbnail ausgesucht werden.
    * Es muss manuell durchgeskippt werden.
* Keine visuelle Vorstellung des Themas.
    * Durch VLC, ist zwar eine Wiedergabe möglich dies ist aber unnötig kompliziert.
* Nicht in der LPRT-Ökonomie eingebaut, was einen schnellen Workflow nahezu unmöglich macht.

## 💡 Lösungen

Jetzt erstmal zusammengefasst.
TEALP wird ein All-In-One Tool

* Es sollten alle Daten sofort auf Knopfdruck kopierbar sein.
* Das extrahieren wird mit der gleichen Methode wie in LPRT erleichtert. Ausgenommen die Random Images.
* Dieses Tool wird eine Datenbank benötigen.
* Es sollen Thumbnail Vorschläge gemacht werden(wird vermutlich später auch bei LPRT eingebaut). 3 - 5 Bilder zufällig.


## 🚧 Datenbank

* Wir wollen das der User Hints oder auch kleine Ideen in ein Eingabefeld eintragen und später wieder auslesen kann.
* Es ist wichtig immer die aktuelle Videopreview mit oder ohne Ingamesound wiedergeben zu können.
* Die Daten werden von LPRT in `CSV` Format exportiert und bei TEALP importiert. Hier wird dann die Datenbank zusammengebaut und gespeichert.
* Es sollen externe Daten wie die exports von Krita wieder reimportiert werden.


## Extrahieren von Thumbnails(raw)

Wir werden wie auch schon in LPRT, Thumbnails mit `FFMPEG` extrahiert.


## Bearbeiten von Thumbnails

## Speichern von Thumbnails

## Integration zu LPRT