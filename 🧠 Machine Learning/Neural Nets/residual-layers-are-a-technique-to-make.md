## Note
nid: 1629297004768
model: Basic-d7a3e-4ce08
tags: checklater, ml::11_rnns
markdown: false

### Front
Residual layers are a technique to make networks deeper.
<div>
  Explain them.
</div>

### Back
<div>
  In networks with residual blocks, each layer feeds into the next
  layer and directly into the layers about 2-3 hops away.
</div>
<div>
  Use network layers to fit a <b>residual mapping</b> instead of
  directly trying to fit a desired underlying mapping.
</div>
<div>
  Use layers to fit residual \(F(x)=H(x)-x\) instead of \(H(x)\)
  directly. H(x) is the true distribution, we would like to learn.
  Learining \(F(x)=H(x)-x\) is much easier.
</div>
<div>
  Initially, \(F(x)\) is set to 0, so the layer just computes the
  identity.
</div>
<div>
  In the image below one has an identity connection from \(x\), so
  the layers are actually traing to learn the residuals \(F(x)\).
  Hence, the residual block.
</div>
<div><img src=
"paste-a795048d2bef92bdbe249d3a19081382d6fa2a52.jpg"></div>
