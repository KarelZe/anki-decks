## Note
nid: 1629612871123
model: Basic-d7a3e-4ce08
tags: checklater, ml::02_linear_classification
markdown: false

### Front
How can one derive the <b>cross-entropy loss</b> for <b>logistic
regression</b> using the <b>conditional Bernoulli
log-likelihood</b>?
<div>
  Conditional Bernoulli distribution is given by:
</div>
<div>
  \(p(c \mid \boldsymbol{x})=p(c=1 \mid \boldsymbol{x})^{c} p(c=0
  \mid \boldsymbol{x})^{1-c}\)
</div>
<div>
  Logistic function is given by:
</div>
<div>
  \(\sigma(x)=\frac{1}{1+\exp (-x)}\)
</div>

### Back
\(\begin{aligned} \log \operatorname{lik}(\tilde{\boldsymbol{w}}, D) &=\sum_{i} \log p\left(c_{i} \mid \boldsymbol{x}_{i}\right)=\sum_{i} \log \left(p\left(c=1 \mid \boldsymbol{x}_{i}\right)^{c_{i}} p\left(c=0 \mid \boldsymbol{x}_{i}\right)^{1-c_{i}}\right) \\ &=\sum_{i} c_{i} \log p\left(c=1 \mid \boldsymbol{x}_{i}\right)+\left(1-c_{i}\right) \log p\left(c=0 \mid \boldsymbol{x}_{i}\right) \\ &=\sum c_{i} \log \sigma\left(\tilde{\boldsymbol{w}}^{T} \tilde{\boldsymbol{x}}_{i}\right)+\left(1-c_{i}\right) \log \left(1-\sigma\left(\tilde{\boldsymbol{w}}^{T} \tilde{\boldsymbol{x}}_{i}\right)\right) \end{aligned}\)
