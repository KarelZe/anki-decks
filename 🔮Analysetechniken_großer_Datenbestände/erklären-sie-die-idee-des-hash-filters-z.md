## Note
nid: 1632810853504
model: Basic-d7a3e
tags: 07_association_rules, ultra
markdown: false

### Front
Erklären Sie die <b>Idee</b> des <b>Hash-Filters</b> zur
Optimierung von <b>Apriori.</b>

### Back
<div>
  Man benutzt hashing, um unnötige Itemsset für die nächste
  Kandidaten-Itemset-Generierung herauszufiltern.
</div>Beim Support-Counting im \(k\)-ten Schritt von \(C_k\) (Scan
der DB) sammelt man bereits Informationen \(k+1\)-elementigen
Candidate Itemsets, indem alle möglichen \((k+1)\)-elementigen
Itemsets jeder Transaktion in einer Hash-Table geshasht werden.
<div>
  Man zählt zunächst das Vorkommen der Items aus Transaktionen in
  Tabelle und inkrementiert bei Vorkommen einen Zähler z. B. \(t_1
  = \{1, 2\}\), \(t _2 = \{2\}\), dann wäre \(1=2\) und \(2 = 1\).
  Count in Bucket gibt damit an, wie viele Itemsets in den Bucket
  gehasht wurden.
</div>
<div>
  Alle möglichen \(k+1\)-elementigen Teilmengen einer Transaktion
  \(t\) werden in eine Hashtabelle \(H_{k+1}\) gehasht, wobei in
  jedem Bucket die Anzahl der darauf gehashten Teilmengen vermerkt
  wird z. B. {5, 7} wird gehasht zu \(5 \mod 7 + 7 \mod 7 = 5\).
</div>
<div>
  Bei der Generierung von \(C_{k+1}\) wird dann mit der Hashtabelle
  \(H_{k+1}\) grob überprüft, ob Support für ein \(c \in C_{k+1}\)
  überhaupt gegeben ist. Dadurch können viele Candidate Itemsets
  ausgeschlossen werden, bevor Support-Counting auf Datenbank
  erfolgt.
</div>
<div>
  <b>Beispiel</b>:
</div>
<div><img src=
"paste-971aea7bd5e0d9b67d3fab9c61dee0b5f1d14a8a.jpg"></div>
<div>
  Man bestimmt Support für
  \(C_{1}=\{\{A\},\{B\},\{C\},\{D\},\{E\}\}\) durch Scan der DB.
  Gleichzeitig Aufbau des HashTrees. Alle 2-elementigen Teilmengen
  werden dann aus den Transaktionen erzeugt und in \(H_2\)
  gehashed. \(L_1\) und \(C_2\) (final) verkleinert sich, weil
  einmal richtiger Support nicht erreicht wurde und einmal Support
  in Bucket.
</div>
<div><img src=
"paste-88c16db223fe5ef433da9ea2837f8b07cba8ce65.jpg"></div>
