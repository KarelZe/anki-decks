## Note
nid: 1644132539798
model: Basic-02d89
tags: 02_linear_classification, checklater
markdown: false

### Front
How could the <b>sigmoid function</b> be applied to <b>linear classification</b>?

### Back
Minimize loss:
\(L(\boldsymbol{w})=\sum_{i}\left(\sigma\left(f\left(\boldsymbol{x}_{i}\right)\right)-c_{i}\right)^{2}=\sum_{i}\left(\sigma\left(\boldsymbol{w}^{T} \boldsymbol{x}+b\right)-c_{i}\right)^{2}\)
