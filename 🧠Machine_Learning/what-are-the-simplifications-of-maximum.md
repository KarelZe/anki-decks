## Note
nid: 1630655485069
model: Basic-d7a3e
tags: 09_bayesian_learning, ultra
markdown: false

### Front
What are the simplifications of <b>Maximum a-posteriori solution</b> over Bayesian Learning?

### Back
Find parameter vector \(\boldsymbol{\theta}_{\text{MAP}}\) that maximizes the posterior:<div>\(\boldsymbol{\theta}_{MAP}=\underset{\boldsymbol{\theta}}{\arg \max } p(\boldsymbol{\theta} \mid \mathcal{D})=\underset{\boldsymbol{\theta}}{\arg \max } p(\mathcal{D} \mid \boldsymbol{\theta}) p(\boldsymbol{\theta})\)
</div><div>
</div><div>Uncertainty in \(\boldsymbol{\theta}\) is ignored. </div><div>Optimization is done in log-domain.</div><div>\(\log p(\boldsymbol{\theta})\) is the difference to the maximum likelihood solution.
</div><div>
</div><div> \(\boldsymbol{\theta}_{MAP}=\underset{\theta}{\arg \max } \log p(\mathcal{D} \mid \boldsymbol{\theta})+\log p(\boldsymbol{\theta})\)</div><div>
</div><div>Use \(\boldsymbol{\theta}_{MAP}\) for prediction</div><div>\(p\left(\boldsymbol{x}^{*} \mid \mathcal{D}\right) \approx p\left(\boldsymbol{x}^{*} \mid \boldsymbol{\theta}_{MAP}\right)\)
</div><div>
</div>
