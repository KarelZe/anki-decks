## Note
nid: 1605359127189
model: Basic-d7a3e
tags: 02_linear_classification, checklater
markdown: false

### Front
<p>Was ist die zentrale Idee der <b>Monte-Carlo Schätzung</b>?</p>

### Back
<p>\[\mathbb{E}_{p}[f(x)]=\int p(x) f(x) d x \approx \frac{1}{N}
\sum_{x_{i} \sim p(x)} f\left(x_{i}\right)\]
<p>Notwendig, wenn keine analytische Lösung existiert, um das
Integral zu lösen. Man zieht möglichst viele Samples aus \(p(x)\).
