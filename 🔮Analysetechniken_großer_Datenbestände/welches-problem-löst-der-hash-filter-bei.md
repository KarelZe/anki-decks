## Note
nid: 1632809878461
model: Basic-d7a3e
tags: 07_association_rules
markdown: false

### Front
Welches <b>Problem</b> löst der <b>Hash-Filter</b> bei Apriori (<i>Candidate Itemset Reduction</i>)?

### Back
Oft hat man viele large 1-itemsets, dementsprechend ist
\(\left|L_{1}\right|\) sehr groß.
<div>
  Für die Menge der daraus resultierenden Candidate Itemsets ergibt
  sich
  \(\left|C_{2}\right|=\left(\begin{array}{c}\left|L_{1}\right| \\
  2\end{array}\right)\).
</div>
<div>
  Es gilt, je mehr Itemsets man in \(C_{k}\) hat, desto größer sind
  die Kosten zur Erstellung von \(L_k\) (Support-Counting). Man
  möchte also frühzeitig die Größe von \(C_2\) verringern, indem
  man beim Support-Counting im \(k\)-ten Schritt Informationen über
  mögliche \((k+1)\)-elementige <i>Candidate Itemsets</i> sammelt.
</div>
