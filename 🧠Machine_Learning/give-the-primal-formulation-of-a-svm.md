## Note
nid: 1629010630483
model: Basic-d7a3e
tags: 08_svm, checklater
markdown: false

### Front
Give the <b>primal formulation</b> of a SVM.

### Back
\[\begin{aligned}
\operatorname{argmin}_{\mathbf{w}, \boldsymbol{\xi}} &\|\mathbf{w}\|^{2}+C \sum_{i}^{N} \xi_{i}, \\
\text { s.t. } & y_{i}\left(\mathbf{w}^{T} \mathbf{x}_{i}+b\right) \geq 1-\xi_{i}, \quad \xi_{i} \geq 0
\end{aligned}\]
