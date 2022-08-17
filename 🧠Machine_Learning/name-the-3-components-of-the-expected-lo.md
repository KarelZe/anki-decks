## Note
nid: 1629450221378
model: Basic-d7a3e
tags: 03_model_selection, checklater
markdown: false

### Front
Name the 3 components of the expected loss.

### Back
\(\text { Expected Loss }=\text { Variance }+\text { Bias
}^{2}+\text { Noise }\)
<div>
  \(\begin{aligned} R\left(\hat{f}_{D_{n}}\right)
  &=\mathbb{E}_{D_{n}}\left[\mathbb{E}_{x,
  y}\left[\left(\hat{f}_{D_{n}}(x)-y\right)^{2}\right]\right] \\
  &=\underbrace{\mathbb{E}_{D_{n}}\left[\mathbb{E}_{x,
  y}\left[\left(\hat{f}_{D_{n}}(x)-\hat{f}_{*}(x)\right)^{2}\right]\right]}_{\text
  {Variance }}+\underbrace{\mathbb{E}_{x,
  y}\left[\left(\hat{f}_{*}(x)-f(x)\right)^{2}\right]}_{\text {Bias
  }^{2}}+\underbrace{\sigma^{2}}_{\text {noise }} \end{aligned}\)
</div>
