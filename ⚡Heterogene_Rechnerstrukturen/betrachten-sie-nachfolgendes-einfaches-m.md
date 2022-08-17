## Note
nid: 1611765060172
model: Basic-b122e
tags: 04_koheraenz, 11_para_block_prozess
markdown: false

### Front
Betrachten Sie nachfolgendes einfaches Multiprozessorsystem mit 2
Prozessoren.
<div>
  <div><img src="11071569.png"></div>
</div>
<div>
  Ein Pfeil steht für Adressbus, der andere für Datenbus.
</div>
<div>
  Rotes Rechteck repräsentiert Speicherblock, der in Caches geholt
  wird.
</div>
<div>
  Vollziehen Sie nach, welche Zustandsübergänge beim MESI-Protokoll
  bei 4 aufeinander folgenden Zugriffen auf ein und denselben
  Speicherblock erfolgen?
</div>

### Back
<img src="28104388.png"><div>
</div><div>2. Prozessor beobachtet, dass Leseoperation durchgeführt wird.</div><div>
</div><div>Exclusive Read miss liegt vor. Eintrag ist nicht vorhanden.</div><div>
</div><div>Cachezeile, in die der Block geladen wird, geht vom Zustand invalid in Zustand exclusive.</div><div>
</div><img src="81624736.png"><div>Anschließend führen wir ein Lesen auf die Adresse 8 durch. Block muss aus dem Hauptspeicher geladen werden.</div><div>
</div><div>Prozessor 1 beobachtet Lesezugriff auf Adresse, die er in seinem Cache findet (Snoop Hit on a Read). Prozessor schickt shared Signal. Cachezeile wechselt in den Zustand shared.</div><div><div>
</div><img src="52990270.png"></div><div>Prozessor 1 verändert Wert z. B. 500. Wir ändern Cachezeile von shared in Zustand modified.</div><div>
</div><div>Wir schicken dann invalid Signal, anderer Prozessor invalidiert Block mit dieser Adresse.</div><div><div>
</div><img src="60387747.png"></div><div>
</div><div>Cachezeile ist ungültig. Wir haben Fehlzugriff. Lesezugriff führt zu Treffer im Cache (Snoop Hit on a Read). Wir schicken dann das Retry-Signal. Prozessor 2 unterbricht Laden des Blocks aus Hauptspeicher.</div><div>
</div><div>Prozessor 1 wechselt in Zustand shared.</div><div>
</div><div>Das wird wieder von Prozessor 2 beobachtet. Wir haben Snoop-Hit on a Read. Wir gehen in Zustand shared über.</div>
