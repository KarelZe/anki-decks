## Note
nid: 1609155708277
model: Basic-d7a3e-4ce08
tags: ml::06_em_for_dim_reduction, ultra
markdown: false

### Front
<p>How does the EM algorithm work? What are its main steps?

### Back
<p><b>Expectation step</b>
<p>\(q(z)=\underset{q}{\arg \min } \mathrm{KL}(q(z) \| p(z \mid
\boldsymbol{x}))\)
<p>Find \(q(z)\) (distribution of latent variable) that minimizes
KL.
<p>Can be done in closed form for discrete \(\boldsymbol{z}\) (e.
g. mixtures)
<p>\(q(z)=p\left(z \mid \boldsymbol{x}, \boldsymbol{\theta}_{\text
{old }}\right)=\frac{p\left(\boldsymbol{x}, z \mid
\boldsymbol{\theta}_{\text {old }}\right)}{\sum_{z}
p\left(\boldsymbol{x}, z \mid
\boldsymbol{\theta}_{\mathrm{old}}\right)}\)
<p><b>Maximization step:</b>
<p>\(\boldsymbol{\theta}=\underset{\boldsymbol{\theta}}{\arg \max }
\mathcal{L}(q,
\boldsymbol{\theta})=\underset{\boldsymbol{\theta}}{\arg \max }
\sum_{z} q(z) \log p(\boldsymbol{x}, z \mid
\boldsymbol{\theta})+\text { const }\)
<p>Maximize lower bound with respect to \(\boldsymbol{\theta}\)
<p>Also called the complete-data likelihood
<p>Each possible value of the missing data is weighted by:
<p>\(q(z)=p\left(z \mid \boldsymbol{x}, \boldsymbol{\theta}_{\text
{old }}\right)\)
