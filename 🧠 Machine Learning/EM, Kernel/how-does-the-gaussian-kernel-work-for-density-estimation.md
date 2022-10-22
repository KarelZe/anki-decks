# Note
```
guid: NiKu+pS-ov
notetype: Basic-d7a3e-4ce08
```

### Tags
```
ml::06_em_for_dim_reduction
ultra
```

## Front
How does the <b>Gaussian kernel</b> work for <b>density
estimation</b>?

## Back
<b>Kernel function:</b>
<div>
  \(g(\boldsymbol{u})=\exp \left(-\frac{\|\boldsymbol{u}\|^{2}}{2
  h}\right)\)
</div>
<div>
  <b>Volume:</b>
</div>
<div>
  \(V=\int g(\boldsymbol{u}) d \boldsymbol{u}=\sqrt{2 \pi h^{d}}\)
</div>
<div>
  <b>Estimated density:</b>
</div>
<div>
  \(\begin{aligned} p\left(\boldsymbol{x}_{*}\right) & \approx
  \frac{1}{N V} \sum_{i=1}^{N}
  g\left(\boldsymbol{x}_{*}-\boldsymbol{x}_{i}\right) \\
  &=\frac{1}{N \sqrt{2 \pi h^{d}}} \sum_{i=1}^{N} \exp
  \left(-\frac{\left\|\boldsymbol{x}_{*}-\boldsymbol{x}_{i}\right\|^{2}}{2
  h}\right) \end{aligned}\)
</div>
