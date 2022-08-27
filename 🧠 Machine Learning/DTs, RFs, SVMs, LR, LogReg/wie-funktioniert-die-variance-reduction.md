## Note
nid: 1607185374269
model: Basic-d7a3e-4ce08
tags: checklater, ml::04_trees_rf
markdown: false

### Front
<p>Wie funktioniert die <b>Variance Reduction</b> bei <b>Random
Forests</b>?

### Back
<p><b>Im Allgemeinen:</b>
<p>\(\operatorname{Var}\left[\frac{1}{M} \sum_{i=1}^{M}
X_{i}\right]=\frac{1}{M^{2}} \operatorname{Var}\left[\sum_{i=1}^{M}
X_{i}\right]=\frac{1}{M} \operatorname{Var}[X], \quad \text { if }
X \text { i.i.d. }\)
<p>Idealerweise würde die Varianz linear mit der Zahl der Bäume
sinken.
<p><b>In der Praxis:</b>
<p>\(\operatorname{Var}\left[\frac{1}{M} \sum_{i=1}^{M}
\operatorname{Tree}_{i}\right]>\frac{1}{M} \text { Var [Tree],
as trees are still correlated }\)
