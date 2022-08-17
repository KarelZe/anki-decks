## Note
nid: 1632549087997
model: Basic-d7a3e
tags: 06_association_rules, checklater
markdown: false

### Front
Wie erfolgt die Verwendung eines Hash Trees bei Apriori?

### Back
<div>
  Hash Tree soll das Support-Counting beschleunigen. Es werden
  gewissermaßen mehrere Vergleiche auf einmal durchgeführt. Man
  muss auch nicht jedmögliche Teilmenge prüfen.
</div>
<div><img src="406567_FeyoloviLiwuYoGu3435477688112491.png"></div>
<div>
  <div>
    Man konstruiert Hash-Tree für Kandidaten. Items sind sortiert.
    Im Hash-Tree entspricht die erste Ebene der 1. Position im
    Kandidaten. Die 2. Ebene der 2. Position usw. Um Position von
    Kandidaten im Baum zu finden, würde man Ebenenweise hinabgehen.
    Es erfolgt aber ein Hashing, so landet {1,3,5} und {1,3,9} im
    selben Knoten wegen Hash 1 bei Mod 4. Hashfunktion macht baum
    kompakter.
  </div>
  <div>
    Um zu überprüfen, was gültige Teilmengen von t = {1,2,3,5}
    sind, würde man den Baum beginnend mit 1 und 2 wegen {1,2,3}
    und {2,3,5} hinabsteigen. Mit 3 kann keine Teilmenge beginnen
    wegen Sortierung. Man steigt dann hinab nach {1,2,3}. Dort
    würde man vergleichen ob Itemset {1,2,3} Teilmenge der
    Transaktion ist. Könnte ja auch {1,2,7} sein wegen selbem Hash.
  </div>
</div>
