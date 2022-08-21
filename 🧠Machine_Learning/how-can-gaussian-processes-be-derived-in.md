## Note
nid: 1631173389660
model: Basic-d7a3e
tags: 09_bayesian_learning
markdown: false

### Front
How can Gaussian processes be derived in weight-space view?

### Back
We can use the posterior to evaluate the predictive distribution using the Kernel trick.<div>\(\begin{aligned} p\left(y^{*} \mid \boldsymbol{x}^{*}, \boldsymbol{X}, \boldsymbol{y}\right) &=\int p\left(y^{*} \mid \boldsymbol{w}, \boldsymbol{x}^{*}\right) p(\boldsymbol{w} \mid \boldsymbol{X}, \boldsymbol{y}) d \boldsymbol{w} \\ &=\int \mathcal{N}\left(y_{*} \mid \boldsymbol{\phi}_{*}^{T} \boldsymbol{w}, \sigma_{\boldsymbol{y}}^{2}\right) \mathcal{N}\left(\boldsymbol{w} \mid \boldsymbol{\mu}_{\boldsymbol{w} \mid \boldsymbol{X}, \boldsymbol{y}}, \boldsymbol{\Sigma}_{\boldsymbol{w} \mid \boldsymbol{X}, \boldsymbol{y}}\right) d \boldsymbol{w} \end{aligned}\)
</div><div>
</div><div>Mean:</div><div>\(\begin{aligned} \mu\left(\boldsymbol{x}^{*}\right) &=\lambda^{-1} \boldsymbol{\phi}\left(\boldsymbol{x}^{*}\right)^{T} \boldsymbol{\Phi}^{T}\left(\sigma_{\boldsymbol{y}}^{2} \boldsymbol{I}+\boldsymbol{K}\right)^{-1} \boldsymbol{y} \\ &=\boldsymbol{k}\left(\boldsymbol{x}^{*}\right)^{T}\left(\sigma_{\boldsymbol{y}}^{2} \boldsymbol{I}+\boldsymbol{K}\right)^{-1} \boldsymbol{y} \end{aligned}\)
</div><div>
</div><div>Variance:</div><div>\(\begin{aligned} \sigma\left(\boldsymbol{x}^{*}\right) &=\sigma_{y}^{2}+\lambda^{-1} \boldsymbol{\phi}\left(\boldsymbol{x}^{*}\right)^{T} \boldsymbol{\phi}\left(\boldsymbol{x}^{*}\right)-\lambda^{-2} \boldsymbol{\phi}\left(\boldsymbol{x}^{*}\right)^{T} \boldsymbol{\Phi}^{T}\left(\sigma_{\boldsymbol{y}}^{2} \boldsymbol{I}+\boldsymbol{K}\right)^{-1} \boldsymbol{\Phi} \phi\left(\boldsymbol{x}^{*}\right) \\ &=\sigma_{y}^{2}+k\left(\boldsymbol{x}^{*}, \boldsymbol{x}^{*}\right)-\boldsymbol{k}\left(\boldsymbol{x}^{*}\right)^{T}\left(\sigma_{\boldsymbol{y}}^{2} \boldsymbol{I}+\boldsymbol{K}\right)^{-1} \boldsymbol{k}\left(\boldsymbol{x}^{*}\right) \end{aligned}\)
</div><div>
</div><div>
</div><div>
</div>
