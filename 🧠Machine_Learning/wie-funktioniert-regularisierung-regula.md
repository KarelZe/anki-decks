## Note
nid: 1607431950442
model: Basic-d7a3e
tags: 02_linear_classification
markdown: false

### Front
<p>Wie funktioniert <b>Regularisierung</b> <i>(Regularization)</i> bei <b>Logistischer Regression</b>?</p>

### Back
<p>On can add a <b>regularization penalty</b>:
<p>\(L(\tilde{\boldsymbol{w}}, D)=\log
\operatorname{lik}(\tilde{\boldsymbol{w}}, D)-\lambda
\operatorname{penalty}(\tilde{\boldsymbol{w}})\)
<p>\(\ell_2\) is commonly used:
<p>
\(\operatorname{penalty}(\tilde{\boldsymbol{w}})=\|\tilde{\boldsymbol{w}}\|^{2}\)
