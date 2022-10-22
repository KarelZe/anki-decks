# Note
```
guid: MoPjFm7sok
notetype: Basic-d7a3e-4ce08
```

### Tags
```
checklater
ml::02_linear_classification
```

## Front
<p>Was sind die jeweils gängigen Ansätze für die Regularisierung
von Linearen Klassifizierern und Linearen Regressionsmodellen?

## Back
<p><b>Least squares solution:</b>
<p>\(\operatorname{argmin}_{\boldsymbol{w}}
\operatorname{SSE}(\boldsymbol{w}, D)+\lambda
\operatorname{penalty}(\boldsymbol{w})\)
<p><b>Maximum likelihood solution:</b>
<p>\(\operatorname{argmax}_{\boldsymbol{w}} \log
\operatorname{lik}(\boldsymbol{w}, D)-\lambda
\operatorname{penalty}(\boldsymbol{w})\)
<p>(Recall that \(\underset{\boldsymbol{x}}{\arg \min }
f(\boldsymbol{x})=\underset{\boldsymbol{x}}{\arg \max
}-f(\boldsymbol{x})\). Therefore, penalty is subtracted.)
