## Note
nid: 1629010720979
model: Basic-d7a3e-4ce08
tags: checklater, ml::08_svm
markdown: false

### Front
Give the <b>dual formulation</b> of a SVM.

### Back
\[
\begin{aligned}
&\max _{\boldsymbol{\lambda}} \sum_{i} \lambda_{i}-\frac{1}{2} \sum_{i} \sum_{j} \lambda_{i} \lambda_{j} y_{i} y_{j} \boldsymbol{k}\left(\boldsymbol{x}_{i}, \boldsymbol{x}_{j}\right) \\
&\text { s.t. } C \geq \lambda_{i} \geq 0, \forall i \in[1 \ldots N], \quad \sum_{i} \lambda_{i} y_{i}=0
\end{aligned}
\]
