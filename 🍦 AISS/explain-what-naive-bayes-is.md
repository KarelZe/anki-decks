## Note
nid: 1636530791170
model: Basic-d7a3e-4ce08
tags: 03_evaluation, repeat
markdown: false

### Front
Explain what <b>Naive Bayes</b> is.

### Back
Naive Bayes is a variant of the Bayes classifier. It assumes
conditional independence, which means that every feature \(X\) is
statistically independent, and every feature contributes
independently to the probability of its class \(Y\). Therefore, it
can by calculated by:
<div>
  \(Y=\arg \max P(Y) * \prod P(X \mid Y)\)
</div>
