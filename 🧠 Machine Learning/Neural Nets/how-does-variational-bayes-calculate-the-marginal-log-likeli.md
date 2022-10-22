# Note
```
guid: O}FZxuP.Tk
notetype: Basic-02d89-e0e22
```

### Tags
```
ml::12_var_ae
```

## Front
How does <b>Variational Bayes</b> calculate the <b>marginal
log-likelihood</b>?

## Back
Variational Bayes (VB) uses a lower bound of the marginal log-likelihood for the optimization.

For simplicity, lets consider only a single data-point first:
\(\underbrace{\log p(\boldsymbol{x})}_{\text {marginal log-like }}=\underbrace{\int q(\boldsymbol{z}) \log \frac{p(\boldsymbol{x} \mid \boldsymbol{z}) p(\boldsymbol{z})}{q(\boldsymbol{z})} d \boldsymbol{z}}_{\text {Lower Bound } \mathcal{L}(q)}+\underbrace{\int q(\boldsymbol{z}) \log \frac{q(\boldsymbol{z})}{p(\boldsymbol{z} \mid \boldsymbol{x})} d \boldsymbol{z}}_{\text {KL Divergence: } \mathrm{KL}(q(\boldsymbol{z})|| p(\boldsymbol{z} \mid \boldsymbol{x}))}\)

Where \(q(z)\) is called the variational / auxiliary distribution. This decomposition holds for any \(q(\boldsymbol{z})\). By introducing \(\mathrm{q}(\mathrm{z})\), the optimization will become much simpler.

Why is that the same?

We can use Bayes rule for \(p(\boldsymbol{z} \mid x)=\frac{p(\boldsymbol{x}, \boldsymbol{z})}{p(\boldsymbol{x})}\) and all terms except \(p(\boldsymbol{x})\) cancel
VB optimizes the lower bound instead of the log-likelihood:
\[\mathcal{L}(q, p)=\int q(\boldsymbol{z}) \log \left(p(\boldsymbol{x} \mid \boldsymbol{z}) \frac{p(\boldsymbol{z})}{q(\boldsymbol{z})}\right) d \boldsymbol{z}=\int q(\boldsymbol{z}) \log p(x \mid z) d z-\mathrm{KL}(q(\boldsymbol{z}) \| p(\boldsymbol{z}))\]

Why is it a lower bound? Since \(\operatorname{KL}(q \| p) \geq 0\) it follows that \(\mathcal{L}(q, p) \leq \log p(\boldsymbol{x})\)
Its also called Evidence lower bound (ELBO), as the marginal likelihood is often called evidence.

Joint optimization of the lower bound \(\mathcal{L}(q, p)\) w.r.t \(p\) and \(q\) using stochastic gradient descent:
\[q^{*}, p^{*}=\underset{q, p}{\arg \max } \mathcal{L}(q, p)\]

In practice, \(q_{\phi}(\boldsymbol{z}), p_{\varphi}(\boldsymbol{x} \mid \boldsymbol{z})\) and \(p_{\varphi}(\boldsymbol{z})\) will be parametrized distributions and we optimize over \(\phi\) and \(\varphi\).
