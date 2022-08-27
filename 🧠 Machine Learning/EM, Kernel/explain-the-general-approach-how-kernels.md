## Note
nid: 1631080166951
model: Basic-d7a3e-4ce08
tags: ml::06_em_for_dim_reduction
markdown: false

### Front
Explain the general approach how <b>kernels</b> can be used for
<b>density estimation</b>.

### Back
<b>Volume:</b>
<div>
  \(V=\int g(\boldsymbol{u}) d \boldsymbol{u}\)
</div>
<div>
  <b>Summed kernel activation:</b>
</div>
<div>
  \(K\left(\boldsymbol{x}_{*}\right)=\sum_{i=1}^{N}
  g\left(\boldsymbol{x}_{*}-\boldsymbol{x}_{i}\right)\)
</div>
<div>
  <b>Estimated density:</b>
</div>
<div>
  \(p\left(\boldsymbol{x}_{*}\right) \approx
  \frac{K\left(\boldsymbol{x}_{*}\right)}{N V} \equiv \frac{1}{N V}
  \sum_{i=1}^{N}
  g\left(\boldsymbol{x}_{*}-\boldsymbol{x}_{i}\right)\)
</div>
