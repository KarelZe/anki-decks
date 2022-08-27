## Note
nid: 1653718885437
model: Basic-02d89-e0e22
tags: bda::02_classification
markdown: false

### Front
How does <b>training</b> of the <b>Softmax Regression</b> work?

### Back
Compute softmax score for each class
\(s_{k}(\mathbf{x})=\left(\boldsymbol{\theta}^{(k)}\right)^{T}
\mathbf{x}\) where \(\boldsymbol{\theta}^{(k)}\) is a parameter
vector for every \(k\) in parameter matrix \(\Theta\)
<b>Probability</b>: Normalized softmax function
\(\hat{p}_{k}=\sigma(s(\mathbf{x}))_{k}=\frac{\exp
\left(s_{k}(\mathbf{x})\right)}{\sum_{j=1}^{K} \exp
\left(s_{j}(\mathbf{x})\right)}\) <b>Predict</b>:
\(\hat{y}=\operatorname{argmax}_{k} \sigma(s(\mathbf{x}))_{k}\)
Minimize cross entropy cost function (using Gradient Descent):
\(J(\Theta)=-\frac{1}{n} \sum_{i=1}^{n} \sum_{k=1}^{K} y_{k}^{(i)}
\log \left(\hat{p}_{k}^{(i)}\right)\)
