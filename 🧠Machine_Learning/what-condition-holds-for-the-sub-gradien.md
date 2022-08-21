## Note
nid: 1628954957841
model: Basic-d7a3e
tags: 08_svm, checklater
markdown: false

### Front
What condition holds for the <b>sub-gradient</b>?

### Back
\(f\) is a convex function mapping \(\mathbb{R}^{d} \rightarrow
\mathbb{R}\).
<div>
  A subgradient at any point \(\boldsymbol{x}\) is any
  \(\boldsymbol{g}\) (aka the subgradient) such that:
</div>
<div>
  \(f(\boldsymbol{z}) \geq
  f(\boldsymbol{x})+\boldsymbol{g}^{T}(\boldsymbol{z}-\boldsymbol{x})\)
</div>
<div>
  If \(f\) is differntiable at \(\boldsymbol{x}\), then
  \(\boldsymbol{g}=\nabla f(\boldsymbol{x})\).
</div>
