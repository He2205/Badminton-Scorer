# Badminton
Badminton Scorer Punkteanzeige

3 veschiedene Badminton Scorer Boards.

Uns, im Verein, hat es immer wieder genervt, dass eine Diskussion aufkam, wie viel es denn jetzt steht.
Da dachte ich mir, ich bau mal was aus den Teilen die ich zu Hause habe und benutze meinen Ender3 V3 KE mal dazu 
ein funktionelles Board zu erstellen.

Es sollte zwei kleine Buttons haben um die Punkte zu zählen die man im besten Fall am Körper tragen kann ohne das sie stören.
Es sollte auch die Player anzeigen können und auch die Games.
So ist nach und nach ein, so wie ich finde, schönes Board entstanden.
Natürlich ist es ein Prozeß und eigentlich ist man damit nie fertig.

Und verbessern kann man es immer. :-)

Das große Board hat 7cm große 7 Segment Anzeigen und musste somit mit 12 VDC betrieben werden.
Somit musste auch das Max7219 etwas modifiziert werden, da es ja maximal nur mit 5V Anzeigen umgehen kann.
Geholfen hat mir hier die Google suche und es hat auch nach etwas probieren auf dem Steckboard gut funktioniert.
Es sind 3x 18650 Batterien verbaut, die ca 4h - 6h das Board mit Energie versorgen.
Eine Status Anzeige der Batterien ist ebenso verbaut sowie eine USB-C Buchse worüber die 18650 direkt aufgeladen werden können.

Man kann hier auch die Spieler mit Namen eintragen und man kann sogar sehen wer den Aufschlag hat und auf welcher Seite
aufgeschlagen werden muss.
Auch ein Seitenwechsel ist mit drin.

Ausserdem habe ich hier eine IR Fernbedienung integriert um das Menu etwas einfacher zu bedienen.
Gepunktet wird über selbst gebaute Handsender die über ESPNow / ESP01 mit dem ESP8266 Wemos  im Gerät kommunizieren. Zusätzlich kann man 
über die Tasten am Gerät selber und über die IR Fernbedienung punkten.
Auch ein doppelt oder falscher Punktestand lässt sich korrigieren.
Alles learning by doing und mit viel googlen ist ein, mehr schlecht als recht, guter code entstanden den ich in der Arduino IDE 2 geschrieben habe.




