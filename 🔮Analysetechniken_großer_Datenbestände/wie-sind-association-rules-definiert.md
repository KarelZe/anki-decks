## Note
nid: 1606675651047
model: Basic-d7a3e
tags: 06_association_rules
markdown: false

### Front
<p>Wie sind <b>Association Rules</b> definiert?</p>

### Back
<p>\[A \Rightarrow B[s, c],\]
<p>\(A\) und \(B\) sind Itemsets. \([s,c]\) sind Schwellenwerte,
die AR erfüllen muss, analog zum Support bei Frequent Itemsets.
\(s\) ist Support von \(A \Rightarrow B:=\operatorname{support}(A
\cup B)\) und \(c\) ist die Confidence von \(A \Rightarrow
B:=\frac{\text { support }(A \cup B)}{\text { support }(A)}\).
