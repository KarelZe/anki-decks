## Note
nid: 1659615919377
model: Basic-02d89
tags: 12_var_ae_ml
markdown: false

### Front
What is problematic about learning the <b>decoder function</b> in a <b>variational auto-encoder</b>?

### Back
The decoder function is very complicated, so there's no hope of finding a closed form.

The (marginal) Log-Likelihood is <b>computationally infeasible</b>:
\[\log \operatorname{Lik}(\mathcal{D})=\sum_{i=1}^{N} \log p\left(\boldsymbol{x}_{i}\right)=\sum_{i=1}^{N} \log \left(\int p\left(\boldsymbol{x}_{i} \mid \boldsymbol{z}\right) p(\boldsymbol{z}) d \boldsymbol{z}\right) \approx \sum_{i=1}^{N} \log \left(\frac{1}{M} \sum_{\boldsymbol{z}_{j} \sim p(\boldsymbol{z})}^{M} p\left(\boldsymbol{x}_{i} \mid \boldsymbol{z}_{j}\right)\right)\]Requires a <b>lot of samples</b> \(\boldsymbol{z}_{j}m\) for each \(\boldsymbol{x}_{i}\) due to <b>uninformed sampling</b> of \(\boldsymbol{z}_{j}m\) (high variance in \(p(\boldsymbol{x} \mid \boldsymbol{z})\) )
