## Note
nid: 1605359135250
model: Basic-d7a3e-4ce08
tags: ml::01_linear_regression
markdown: false

### Front
<p><span>Welches Maß eignet sich zur Evaluation von
Regressionsmodellen?</span>

### Back
<p>R - Squared:
<p>\[R^{2}=1-\frac{\text { Regression sum of squares }}{\text {
Total sum of squares
}}=1-\frac{\sum_{n=1}^{N}\left(\hat{y}_{n}-y_{n}\right)^{2}}{\sum_{n=1}^{N}\left(y_{n}-\bar{y}\right)^{2}}\]
<p><b style="letter-spacing: 0.01071em;">Interpretation:</b>
<p>wie viel der Variation in \(y\) durch \(x\) erklärt wird.
<p style= 
"font-weight:400;letter-spacing:0.12852px;text-indent:0px;text-transform:none;white-space:normal;word-spacing:0px">
\(R^2 = 1\) Bedeutet, dass gesamte Fehler erklärt wäre
<p style= 
"font-weight:400;letter-spacing:0.12852px;text-indent:0px;text-transform:none;white-space:normal;word-spacing:0px">
\(R^2 = 0\) bedeutet, dass der Regressor schlecht funktioniert
wird.
