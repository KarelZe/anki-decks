## Note
nid: 1620473229111
model: Basic-b122e
tags: 07_lecture_rf_dc
markdown: false

### Front
Explain an approach to split <b>numeric variables</b> in decision trees.

### Back
Let \(n\) denote the number of examples in the training sample. Then, if \(x\) is ordered, the observations in the training sample contain at most \(n\) distinct values \(x_{1}, x_{2}, \ldots, x_{n}\) . of \(x\). This means there are at most \(n-1\) distinct splits of type \(x \leq c_{m}, m=1, \ldots, n \leq n\), where the \(c_{m}\) are taken halfway between consecutive distinct values of \(x\).
