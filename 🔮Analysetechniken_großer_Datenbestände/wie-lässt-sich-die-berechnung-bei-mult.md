## Note
nid: 1608984941409
model: Basic-d7a3e
tags: 06_association_rules, checklater
markdown: false

### Front
<p><span>Wie lässt sich die Berechnung bei Multi-Level Association
Rules mittels einer kodierten TA-Tabelle beschleunigen?</span>

### Back
<p>Verwendung einer <b>kodierten Transaktionstabelle</b> und einer <b>zweidimensionalen Itemset-Tabelle.</b></p><p>Item wird z. B. mit {111} kodiert, womit angeben wird, wo man sich in Hierarchie befindet z. B. 1= Milch, 11 = Diätmilch und 111 = Diätmilch Ja.</p><p><b>Beispiel:</b></p><p><b>Kodierte Transaktionstabelle:</b></p><p><img src="1LEVSqrxyHeYiWQ2KBcq.png" style="width: 284px;"></p><p>111 steht z. B. für Diätmilch Ja!</p><p><b>Itemset-Tabelle</b></p><p>Tabelle \(L[i,j]\) ist zwei-dimensional. \(i\) gibt die Hierarchiebene an und \(j\) die Größe des Itemsets.</p><p><img src="1nhyMk4pHvLFV2cSZwUB.png" style="width: 366px;">
</p><p>L[2,1] bedeutet hier Hierarchiebene 2 und Größe der Itemsets \(i\).</p><p>Man wendet Apriori einmal für verschiedene Hierarchiebenen (level) an. Man hat dann mehrere Kandidaten der Größe 1 z. B. einmal abstrakt (Milch) und einmal spezifisch ("Diätmilch") generiert. Braucht nur genauso viele Scans über DB wie klassischer Apriori.</p>
