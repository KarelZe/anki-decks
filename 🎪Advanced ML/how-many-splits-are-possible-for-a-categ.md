## Note
nid: 1620474209521
model: Basic-b122e
tags: 07_lecture_rf_dc
markdown: false

### Front
How many splits are possible for a categorical variable \(x\) with \(L\) distinct values?

### Back
There are \(2^{L}-2\) non-empty proper subsets of \(V(x)\) (i.e. the empty subset and \(V(x)\) itself are no splits at all). But the splits \(x \in S\) and \(x \in S^{c}\), where \(S^{c}\) is the complement of \(S\) with respect to \(V(x)\), are clearly the same. So the number of different splits is only

\[\frac{1}{2}\left(2^{L}-2\right)=2^{-1} 2^{L}-1=2^{L-1}-1\]
