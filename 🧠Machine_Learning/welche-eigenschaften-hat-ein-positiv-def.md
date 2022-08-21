## Note
nid: 1610191727903
model: Basic-d7a3e
tags: 07_kernel_methods, checklater
markdown: false

### Front
Welche <b>Eigenschaften</b> hat ein <b>positiv-definiter
kernel</b>?

### Back
Ein positiv-definiert kernel \(k\) ist eine Funktion \(k:
\mathcal{X} \times \mathcal{X} \rightarrow \mathbb{R}\) die:
<div>
  <div>
    <div>
      <ul>
        <li><b>Symmetrisch</b>: \(\quad \forall x, x^{\prime}:
        k\left(x, x^{\prime}\right)=k\left(x^{\prime}, x\right)\)
        <li><b>Ähnlichkeitsmatrix</b> ist immer positiv-definit:
        \(\boldsymbol{a}^{T} \boldsymbol{K}
        \boldsymbol{a}=\sum_{i=1}^{n} \sum_{j=1}^{n} a_{i} a_{j}
        k\left(\boldsymbol{x}_{i}, \boldsymbol{x}_{j}\right) \geq
        0, \quad \forall \boldsymbol{a}, \forall
        S=\left\{\boldsymbol{x}_{1}, \ldots,
        \boldsymbol{x}_{n}\right\}\) Muss für jeden Vektor
        \(\boldsymbol{a}\) gelten.
      </ul>
    </div>
  </div>
</div>
