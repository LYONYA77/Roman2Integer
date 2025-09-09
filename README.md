# Roman2Integer
Ein Python-Programm, das römische Zahlen automatisch in normale Zahlen umwandelt. Unterstützt alle üblichen römischen Regeln, inklusive Subtraktion.

Dieses Programm wandelt römische Zahlen (wie III, LVIII oder MCMXCIV) in normale Zahlen (wie 3, 58 oder 1994) um.

Programmiersprache
-Python

Funktionsweise

-Das Programm speichert die Werte aller römischen Symbole (I = 1, V = 5, X = 10 usw.).
-Es geht die römische Zahl von rechts nach links durch.
-Für jedes Symbol prüft das Programm:
  -> Wenn es kleiner als das vorherige Symbol ist → subtrahieren
  -> Ansonsten → addieren
-Am Ende wird die berechnete Zahl zurückgegeben.


Dieses Programm wurde von Leon Schumacher gecodet.
