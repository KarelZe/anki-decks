## Note
nid: 1653718044316
model: Basic-02d89-e0e22
tags: bda::02_classification
markdown: false

### Front
Explain how <b>training</b> of <b>logistic regression</b> works?
What is the <b>cost function</b>?

### Back
Cost function of a single training instance:
\[c(\theta)=\left\{\begin{array}{c} -\log (\hat{p}) \text { if }
y=1 \\ -\log (1-\hat{p}) \text { if } y=0 \end{array}\right.\]
Training set cost function (average over all instances - „log
loss“): \[J(\theta)=-\frac{1}{n} \sum_{i=1}^{n}\left[y^{(i)} \log
\left(\hat{p}^{(j)}\right)+\left(1-y^{(i)}\right) \log
\left(1-\hat{p}^{(j)}\right)\right]\] No known closed-form solution
-> Gradient Descent for training \[\frac{\partial}{\partial
\theta_{j}} J(\theta)=\frac{1}{n}
\sum_{i=1}^{n}\left(\sigma\left(\theta^{T}
\mathbf{x}^{(i)}\right)-y^{(i)}\right) x_{j}^{(i)}\]
<b>Example:</b> <img src= 
"paste-51b0cdd5fba09fc855d1fbbf0e6b250de1033036.jpg">
