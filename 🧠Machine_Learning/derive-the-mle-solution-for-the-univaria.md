## Note
nid: 1629616528065
model: Basic-d7a3e
tags: 02_linear_classification, checklater
markdown: false

### Front
Derive the <b>MLE solution</b> for the univariate <b>Gaussian
density function</b>.
<div>
  \(\log \operatorname{lik}(\boldsymbol{\theta} ; D)=-N \log
  \sqrt{2 \pi \sigma^{2}}-\sum_{i}
  \frac{\left(x_{i}-\mu\right)^{2}}{2 \sigma^{2}}\)
</div>

### Back
<div>
  Estimation of \(\mu\)
</div>
<div>
  \(\begin{aligned} \frac{\partial \log \operatorname{lik}(\mu ;
  D)}{\partial \mu}&=-\sum_{i}
  \frac{2\left(x_{i}-\mu\right)(-1)}{2 \sigma^{2}}=0 \\
  &\sum_{i} x_{i}-N \mu=0 \\ &\mu=\frac{1}{N} \sum_{i}
  x_{i} \end{aligned}\)
</div>
<div>
  Estimation of \(\sigma\)
</div>
<div>
  \(\begin{aligned} \frac{\partial \log \operatorname{lik}(\mu ;
  D)}{\partial \sigma}&=-N \log(\sqrt{2\pi})
  -N\log(\sigma)-\sum_{i} \frac{\left(x_{i}-\mu\right)^{2}}{2
  \sigma^{2}}\\ &=-N\frac{1}{\sigma}+\sum_{i}
  \frac{\left(x_{i}-\mu\right)^{2}}{\sigma^{3}}\\
  &N\sigma^2=\sum_{i} \left(x_{i}-\mu\right)^{2}\\
  &\sigma=\sqrt{\frac{1}{N}\sum_{i} \left(x_{i}-\mu\right)^{2}}
  \end{aligned}\)
</div>
