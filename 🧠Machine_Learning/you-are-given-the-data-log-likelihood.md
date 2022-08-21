## Note
nid: 1629613700743
model: Basic-d7a3e
tags: 02_linear_classification, checklater
markdown: false

### Front
You are given the <b>data log-likelihood</b>:
<div>
  \(\log \operatorname{lik}(\mathcal{D},
  \boldsymbol{w})=\sum_{i=1}^{N} p\left(c_{i} \mid
  \boldsymbol{\phi}\left(\boldsymbol{x}_{i}\right),
  \boldsymbol{w}\right)=\sum_{i=1}^{N} \underbrace{c_{i} \log
  \sigma\left(\boldsymbol{w}^{T}
  \boldsymbol{\phi}\left(\boldsymbol{x}_{i}\right)\right)+\left(1-c_{i}\right)
  \log \left(1-\sigma\left(\boldsymbol{w}^{T}
  \boldsymbol{\phi}\left(\boldsymbol{x}_{i}\right)\right)\right)}_{\operatorname{loss}_{i}
  \ldots \text { loss of the ith sample }}\)
</div>
<div>
  Calculate the loss with respect to \(\boldsymbol{w}\)
  \(\frac{\partial \operatorname{loss}_{i}}{\partial
  \boldsymbol{w}}\).
</div>

### Back
\(\begin{aligned} \frac{\partial \operatorname{loss}_{i}}{\partial \boldsymbol{w}}=& \frac{\partial}{\partial \boldsymbol{w}}\left(c_{i} \log \sigma\left(\boldsymbol{w}^{T} \boldsymbol{\phi}\left(\boldsymbol{x}_{i}\right)\right)+\left(1-c_{i}\right) \log \left(1-\sigma\left(\boldsymbol{w}^{T} \boldsymbol{\phi}\left(\boldsymbol{x}_{i}\right)\right)\right)\right.\\=& c_{i} \frac{1}{\sigma\left(\boldsymbol{w}^{T} \boldsymbol{\phi}\left(\boldsymbol{x}_{i}\right)\right)} \sigma\left(\boldsymbol{w}^{T} \boldsymbol{\phi}\left(\boldsymbol{x}_{i}\right)\right)\left(1-\sigma\left(\boldsymbol{w}^{T} \boldsymbol{\phi}\left(\boldsymbol{x}_{i}\right)\right)\right) \phi\left(\boldsymbol{x}_{i}\right) \\ &+\left(1-c_{i}\right) \frac{1}{1-\sigma\left(\boldsymbol{w}^{T} \boldsymbol{\phi}\left(\boldsymbol{x}_{i}\right)\right)}(-) \sigma\left(\boldsymbol{w}^{T} \boldsymbol{\phi}\left(\boldsymbol{x}_{i}\right)\right)\left(1-\sigma\left(\boldsymbol{w}^{T} \boldsymbol{\phi}\left(\boldsymbol{x}_{i}\right)\right)\right) \phi\left(\boldsymbol{x}_{i}\right) \\=& c_{i}\left(1-\sigma\left(\boldsymbol{w}^{T} \boldsymbol{\phi}\left(\boldsymbol{x}_{i}\right)\right)\right) \phi\left(\boldsymbol{x}_{i}\right)-\left(1-c_{i}\right) \sigma\left(\boldsymbol{w}^{T} \boldsymbol{\phi}\left(\boldsymbol{x}_{i}\right)\right) \phi\left(\boldsymbol{x}_{i}\right) \\=&\left(c_{i}-\sigma\left(\boldsymbol{w}^{T} \boldsymbol{\phi}\left(\boldsymbol{x}_{i}\right)\right)\right) \phi\left(\boldsymbol{x}_{i}\right) \end{aligned}\)
