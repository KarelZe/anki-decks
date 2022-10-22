# Note
```
guid: kK2QW:I!d9
notetype: Basic-02d89-e0e22
```

### Tags
```
dl_cv::02_basics_nn
```

## Front
What is the intuition behind the momentun term with gradient descent?

## Back
Takes the gradient from previous steps into account. That is old
gradient is added to new gradient: \[ \begin{gathered}
\Delta_{\mathrm{t}}=\mu \Delta_{\mathrm{t}-1}-\eta \frac{\partial
L(\boldsymbol{\theta})}{\partial \boldsymbol{\theta}} \\
\boldsymbol{\theta} \leftarrow
\boldsymbol{\theta}+\Delta_{\mathrm{t}} \end{gathered} \]
<b>Consequences:</b> Accelerates if the gradients changes in the
same direction \((\rightarrow\) faster convergence) and reduces the
updates if the gradient changes direction ( \(\rightarrow\) less
fluctuations) Momentum hyperparameter \(\boldsymbol{\mu}\) (usually
\(0.9\) ).
