## Note
nid: 1607431950726
model: Basic-d7a3e
tags: 02_linear_classification, checklater
markdown: false

### Front
<p>Was sind die jeweils gängigen Ansätze für die Regularisierung von Linearen Klassifizierern und Linearen Regressionsmodellen?</p>

### Back
<p><b>Least squares solution:</b>
</p><p>\(\operatorname{argmin}_{\boldsymbol{w}} \operatorname{SSE}(\boldsymbol{w}, D)+\lambda \operatorname{penalty}(\boldsymbol{w})\)
</p><p><b>Maximum likelihood solution:</b></p><p>\(\operatorname{argmax}_{\boldsymbol{w}} \log \operatorname{lik}(\boldsymbol{w}, D)-\lambda \operatorname{penalty}(\boldsymbol{w})\)
</p><p>(Recall that \(\underset{\boldsymbol{x}}{\arg \min } f(\boldsymbol{x})=\underset{\boldsymbol{x}}{\arg \max }-f(\boldsymbol{x})\). Therefore, penalty is subtracted.)</p>
