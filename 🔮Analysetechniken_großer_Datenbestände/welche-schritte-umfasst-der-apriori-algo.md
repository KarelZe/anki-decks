## Note
nid: 1608984938569
model: Basic-d7a3e
tags: 06_association_rules, checklater, ultra
markdown: false

### Front
<p>Welche Schritte umfasst der Apriori-Algorithmus zum Finden von
<b>Frequent Item Sets</b> und <b>Association Rules</b>?

### Back
<p>Apriori ist ein Algorithmus zur schrittweisen <b>Generierung</b>
neuer <b>Frequent Itemsets</b>.
<p>Zunächst beginnt man mit der Erzeugung einelementiger Frequent
Itemsets. Man prüft, indem man die Datenbank scannt, ob die
einzelnen Items öfter vorkommen als der Mindestsupport.
<p>Dann bildet man die \(k\)-elementigen Frequent Itemsets. Am
Anfang steht join & prune Schritt sprich die Generierung von
Kandidaten \(C_k\). Danach folgt das Support Counting, sprich
prüfen, ob Support der Itemsets noch ausreichend hoch ist.
<p><img src="1Jz9pxtm5HdamECkZCwi.png" style="width: 366px;">
<p><b>Join-Schritt:</b> Generierung der Kandidatenmengen \(C_k\).
Ableitung der \(k\)-elementigen Frequent Itemsets aus den
\(k-1\)-elementigen Frequent Itemsets. Elemente der Itemsets werden
topologisch sortiert miteinander verglichen. Unterscheiden sich
zwei \(k-1\)-elementige Itemsets, so kann man diese zu einem neuen
\(k\)-Itemset zusammenfügen. Vermeidet Duplikate! Beispiel:
{<strong>1</strong>,<strong>2</strong>,3};
{<strong>1</strong>,<strong>2</strong>,4} -> {1,2,3,4}
<p><b>Prune-Schritt:</b> Kandidatenmenge \(C_k\) ist Obermenge von
\(L_k\) (Menge häufiger Item-Mengen). Die Mitglieder können also
oder können <b>nicht frequent</b> sein. In jedem Fall sind alle
frequent \(k\) Itemsets in \(C_k\). Prune-Schritt reduziert die
Anzahl der Kandidaten. Ausnutzung Apriori-<b>Eigenschaft</b>: Jedes
(k-1)-elementige Itemset, das nicht frequent ist, kann keine
Teilmenge eines frequent \(k\)-itemsets sein. Betrachtung aller
\(k-1\) Teilmengen der \(k\)-Itemsets. Findet sich eine Teilmenge,
die nicht in \(L_{k-1}\) (Menge häufiger \(k-1\)-elementiger
Itemmengen) vorhanden ist, so ist auch schon das entsprechende
\(k\)-Itemset nicht mehr frequent. Pruning verringert die Anzahl
der noch zu untersuchenden Itemsets.
<p><b>Beispiel</b>: Wenn minsup für {1, 2, 3, 4} erfüllt ist, muss
minsup für jede 3-elementige Teilmenge erfüllt sein, ob alle
3-elementige Teilmengen im Schritt davor in der Menge der
3-elementigen Frequent Itemsets vorhanden sind. Hier: {{1,2,3},
{1,2,4}, {2,3,4}, {1,3,4}}
<p><b>Supportcounting</b>: Der letzte Schritt das Support Counting.
Hierbei werden die Frequent Itemsets weiterverwendet, die in den
betrachteten Transaktionen auch den nötigen Support haben.
<b>Beispiel:</b> Zählen von Support von {1,2,3,4}
<p>Je nachdem Ableitung der AR aus Frequent Itemsets im letzten
Schritt.
<p>Man hört auf, wenn \(L_k \neq \varnothing\)
