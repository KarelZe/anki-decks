## Note
nid: 1659637286155
model: Basic-02d89
tags: 12_var_ae_ml
markdown: false

### Front
How  does expectation maximization work for the optimization of the logliklihood of variational auto encoders?
\[\underbrace{\log p(\boldsymbol{x})}_{\text {marginal log-like }}=\underbrace{\int q(\boldsymbol{z}) \log \frac{p(\boldsymbol{x} \mid \boldsymbol{z}) p(\boldsymbol{z})}{q(\boldsymbol{z})} d \boldsymbol{z}}_{\text {Lower Bound } \mathcal{L}(q)}+\underbrace{\int q(\boldsymbol{z}) \log \frac{q(\boldsymbol{z})}{p(\boldsymbol{z} \mid \boldsymbol{x})} d \boldsymbol{z}}_{\text {KL Divergence: } \mathrm{KL}(q(\boldsymbol{z})|| p(\boldsymbol{z} \mid \boldsymbol{x}))}\]

### Back
Expectation-Maximization uses the same decomposition, but two
separate optimization steps <b>Maximization Step:</b> Keep
\(q(\boldsymbol{z})\) fixed, maximize Lower bound \(\mathcal{L}(q,
p)\) w.r.t. model distribution
\(p_{\boldsymbol{\varphi}}(\boldsymbol{x} \mid \boldsymbol{z})\)
and \(p_{\boldsymbol{\varphi}}(\boldsymbol{z})\)
\[\varphi^{*}=\underset{\varphi}{\arg \max } \mathcal{L}\left(q,
p_{\varphi}\right)\] <b>Expectation Step:</b> Keep model
\(p_{\varphi}(\boldsymbol{x} \mid \boldsymbol{z})\) and
\(p_{\boldsymbol{\varphi}}(\boldsymbol{z})\) fixed, minimize KL
w.r.t \(q\) \[\begin{gathered} q^{*}=\underset{q}{\arg \min }
\operatorname{KL}(q(\boldsymbol{z}) \| p(\boldsymbol{z} \mid
\boldsymbol{x})) \\ \rightarrow
q^{*}(\boldsymbol{z})=p(\boldsymbol{z} \mid \boldsymbol{x})
\end{gathered}\]
