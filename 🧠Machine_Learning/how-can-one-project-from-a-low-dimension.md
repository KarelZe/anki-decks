## Note
nid: 1629649949284
model: Basic-d7a3e
tags: 05_dim_reduction
markdown: false

### Front
How can one project from a low dimensional space to a high dimensional space using the Eigenbasis and the other way around?

### Back
<b>Projection to low-D:</b>
\(\boldsymbol{z}_{i}=\boldsymbol{B}^{T}\left(\boldsymbol{x}_{i}-\boldsymbol{\mu}\right)\)
<b>Reprojection to high-D:</b> \(\quad \tilde{\boldsymbol{x}}_{i}=\boldsymbol{\mu}+\boldsymbol{B} \boldsymbol{z}_{i}\)
with \(\boldsymbol{B}=\left[\begin{array}{lll}\boldsymbol{u}_{1} & \ldots & \boldsymbol{u}_{M}\end{array}\right]\)
