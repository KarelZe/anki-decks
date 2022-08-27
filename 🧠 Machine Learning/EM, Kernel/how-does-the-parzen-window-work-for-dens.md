## Note
nid: 1609155704433
model: Basic-d7a3e-4ce08
tags: ml::06_em_for_dim_reduction, ultra
markdown: false

### Front
<p>How does the <b>parzen window</b> work for <b>density
estimation</b>?

### Back
<p><b>Kernel function:</b> Span a hypercube with dimension \(d\)
and edge length \(h\).
<p>\(g(\boldsymbol{u})= \begin{cases}1, & \left|u_{j}\right| \leq h
/ 2, j=1 \ldots d \\ 0, & \text { else }\end{cases}\)
<p><b>Volume:</b>
<p>\(V=\int g(\boldsymbol{u}) d \boldsymbol{u}=h^{d}\)
<p><b>Estimated density:</b>
<p>\(p\left(\boldsymbol{x}_{*}\right) \approx \frac{1}{N h^{d}}
\sum_{i=1}^{N}
g\left(\boldsymbol{x}_{*}-\boldsymbol{x}_{i}\right)\)
