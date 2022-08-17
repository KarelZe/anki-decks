## Note
nid: 1635271047673
model: Basic-d7a3e
tags: 06_decision_tree
markdown: false

### Front
Give a <b>definition</b> of the <b>entropy</b>.

### Back
Entropy \(H(S)\) is a measure of the amount of uncertainty in the (data) set \(S\) (i.e. entropy characterizes the (data) set \(S\) ).
\[
H(S)=-\sum_{c \in C}p(c) \log _{2} p(\mathrm{c})
\]
Where,
\(S\) - The current (data) set for which entropy is being calculated
\(C-\) Set of classes in \(S\)
\(p(c)-\) The proportion of the number of elements in class \(\mathrm{c}\) to the number of elements in set \(S\)
When \(H(S)=0\), the set \(S\) is perfectly classified (i.e. all elements in \(S\) are of the same class).
