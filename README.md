# Skripte-f-r-Forensik
Skripte für Forensik
SQL-Befehle_Formatieren

Dieses Skript öffnet eine Eingabedatei, eine Ausgabedatei und liest jede Zeile der Eingabedatei. Jede Zeile wird mit einem angegebenen Trennoperator in separate Teile aufgeteilt, und dann werden die Teile in die Ausgabedatei geschrieben. Jeder Teil wird dabei in einer neuen Zeile der Ausgabedatei geschrieben.

Das Skript arbeitet wie folgt:

1. Der Benutzer wird aufgefordert, den Namen der Eingabedatei, den Namen der Ausgabedatei und den Trennoperator einzugeben.
2. Das Skript öffnet die Eingabedatei im Lesemodus und die Ausgabedatei im Schreibmodus.
3. Das Skript iteriert durch jede Zeile der Eingabedatei.
4. Für jede Zeile wird der Trennoperator verwendet, um die Zeile in separate Teile aufzuteilen. Die Teile werden in eine Liste namens **`parts`** gespeichert.
5. Das Skript iteriert durch die **`parts`**Liste und schreibt jeden Teil in eine separate Zeile der Ausgabedatei. **`strip()`** wird verwendet, um Leerzeichen am Anfang und Ende jedes Teils zu entfernen, bevor es in die Ausgabedatei geschrieben wird.
6. Das Skript schließt beide Dateien.

Copy_files_per_input

das Skript durchsucht  eine Datei nach einem String, der vom Benutzer eingegeben wird, und gibt alle Texte aus, die den eingegebenen String enthalten. Das Ergebnis wird in einer Ausgabedatei gespeichert.
