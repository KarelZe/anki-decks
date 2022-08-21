## Note
nid: 1607452836680
model: Basic-d7a3e
tags: 02_linear_classification, 10_neural_networks, checklater
markdown: false

### Front
<p>Was ist die Idee von <b>Mini-Batches</b> bei <b>Gradient
Descent</b>?

### Back
<p>Take subset of samples \(I_{t} \subset\{1, \ldots,
n\},\left|I_{t}\right|=b, b \ll n\) to approximate real gradient:
<p>\[\frac{1}{b} \sum_{i \in I_{t}} l\left(\boldsymbol{x}_{i} ;
\boldsymbol{\theta}\right) \\
\boldsymbol{\theta}_{t+1}=\boldsymbol{\theta}_{t}-\frac{\eta}{b}
\sum_{i \in I_{t}} \nabla_{\boldsymbol{\theta}}
l\left(\boldsymbol{x}_{i} ; \boldsymbol{\theta}_{t}\right)\]
<p>where \(b\) is the number of samples drawn uniformly at random
from the the trainingsets and \(I_{t}\) are the samples themselves.
As they are drawn randomly and uniformly the expectation of the
gradient is unchanged, however variance is much lower.
