# Note
```
guid: H1r,37sfj9
notetype: Basic-d7a3e-4ce08
```

### Tags
```
checklater
ml::08_svm
```

## Front
Give the <b>primal formulation</b> of a SVM.

## Back
\[\begin{aligned}
\operatorname{argmin}_{\mathbf{w}, \boldsymbol{\xi}} &\|\mathbf{w}\|^{2}+C \sum_{i}^{N} \xi_{i}, \\
\text { s.t. } & y_{i}\left(\mathbf{w}^{T} \mathbf{x}_{i}+b\right) \geq 1-\xi_{i}, \quad \xi_{i} \geq 0
\end{aligned}\]
