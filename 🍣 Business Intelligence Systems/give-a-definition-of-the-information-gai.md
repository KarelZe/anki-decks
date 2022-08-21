## Note
nid: 1635271382509
model: Basic-d7a3e
tags: 06_decision_tree
markdown: false

### Front
Give a <b>definition</b> of the <b>information gain</b>:

### Back
Information gain \(I G(A)\) is the measure of the difference in entropy from before to after the set \(S\) is split on an attribute \(A\).
\[
I G(A, S)=H(S)-\sum_{t \in T} p(t) H(t)
\]
Where,
\(H(S)-\) Entropy of set \(S\)
\(T\) - The subsets created from splitting set \(S\) by attribute \(A\) such that \(S=\bigcup_{t \in T} t\)
\(p(t)-\) The proportion of the number of elements in \(t\) to the number of elements in set \(S\)
\(H(t)-\) Entropy of subset \(t\)
