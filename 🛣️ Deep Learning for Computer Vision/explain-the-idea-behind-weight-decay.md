## Note
nid: 1652110771637
model: Basic-02d89
tags: 03_nn_basics_dlcv
markdown: false

### Front
Explain the <b>idea</b> behind <b>weight decay</b>.

### Back
Penalize large weights within the network as these tend to be a sign of an overfit network.
It helps the optimizer to approach the optimum using a desirable path with smaller weights which tend to generalize better.

Add to the objective function \(L(\boldsymbol{x}, y ; \boldsymbol{\theta})\) a punishment term \(\frac{\lambda}{2}\|\boldsymbol{\theta}\|_{2}^{2}\). Commonly weights are regularized \(\ell_1\) and \(\ell_2\) norm.

When using the regularized loss to update the weights, during each update step, the weights are driven towards the origin:

\[
\begin{gathered}
\boldsymbol{\theta} \leftarrow \boldsymbol{\theta}-\eta\left(\frac{\partial L(\boldsymbol{x}, y ; \boldsymbol{\theta})}{\partial \boldsymbol{\theta}}-\lambda \boldsymbol{\theta}\right) \\
\boldsymbol{\theta} \leftarrow(\underbrace{(1-\eta \lambda)}_{\text{Weight shrinkage}} \theta-\eta \frac{\partial L(\boldsymbol{x}, y ; \boldsymbol{\theta})}{\partial \boldsymbol{\theta}}
\end{gathered}
\]
