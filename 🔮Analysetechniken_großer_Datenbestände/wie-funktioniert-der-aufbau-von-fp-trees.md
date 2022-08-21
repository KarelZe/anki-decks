## Note
nid: 1609353651084
model: Basic-d7a3e
tags: 07_association_rules, checklater, ultra
markdown: false

### Front
<p>Wie funktioniert der Aufbau von <b>FP-Trees</b>? Wie das
Ermitteln der Frequent Itemsets. Nennen sie auch die 3 Phasen.

### Back
<p><b>Phase 1</b> "Sortieren der Frequent Items innerhalb einer Transaktion nach gesamthäufigkeit" (1 1/2 Scans)</p><p><img src="1YFgpARCHVm8tzpLkxLz.png" style="width: 366px;">
</p><p><b>Phase 2 "Aufbau des FP-Trees"</b></p><p>FP-Tree besteht aus Baum und Header-Tabelle.</p><p><img src="1F7dxpwB1Eu7mGKK73ex.png" style="width: 366px;"></p><p>Man fügt Transaktionen ein. Haben zwei den selben Präfix, werden keine neuen Zweige erzeugt und nur der Zähler hochgezählt. Ist Postfix verschieden, werden neue Zweige angelegt und der Zähler bei Anlage auf 1 gesetzt.</p><p><img src="1kKekPRi9yrpuUc7LCmP.png" style="width: 364px;"></p><p><b>Phase 3 </b>"Extrahieren der Frequent Itemssets aus FP-Tree im Hauptspeicher"</p><p><img src="12A6zD5DBFE9Q6t1D5bX.png" style="width: 366px;"></p><p><img src="12dJcX1yRCMBXjtBe3z7.png" style="width: 366px;"></p><p>Man setzt alle Zähler auf die von p. Man schaut also ob etwa {f,p} den Mindestsupport erreichen, ob {a, p} den Mindestsupport erreichen (nicht der Fall weil a=2, nicht aber in weiteren Transaktionen vorkommt) usw. Dann erhält man Frequent Itemset. Dann wird p gelöscht aus Baum.</p><p>Man beginnt also mit den Items, die am wenigsten häufig sind. Jeder Schritt extrahiert nur noch mehr die Frequent Itemsets, die das aktuelle Item enthalten, aber keine mehr die vorher bereits aktuell waren z. B. p weil gelöscht.</p>
