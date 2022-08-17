## Note
nid: 1642579010123
model: Basic-02d89
tags: 09_ethics
markdown: false

### Front
Explain <b>fairness</b> through <b>equal opportunity</b>.

### Back
True positive rates are equal for all sensitive groups:

\(\operatorname{Pr}(\hat{Y}=1 \mid Y=1, A=a)=\operatorname{Pr}(\hat{Y}=1 \mid Y=1, A=b)\)

with \(X\) features, \(A\) sensitive features(s), binary outcome \(Y \in\{0,1\}\) and prediction / decision \(\hat{\mathbf{Y}} \in\{0,1\}\).

<b>Example</b>
<ul style=""><li style="">Classifier that predicts if a person does not carry a gun</li><li style="">Classifier satisfies equal opportunity if it correctly predicts "no gun" with the same probability, regardless of gender (or race, etc.)</li></ul><img src="paste-46eef4c601f8a09434a30acb8df502e2875c79c0.jpg">
