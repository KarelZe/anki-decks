## Note
nid: 1628934040432
model: Basic-d7a3e-4ce08
tags: checklater, ml::08_svm
markdown: false

### Front
How can the <b>binary classification</b> problem be rephrased for the <b>SVM</b>?

### Back
Given the training data \(\left(\boldsymbol{x}_{i}, y_{i}\right), \mathrm{i}=1 \ldots \mathrm{N}\), with \(x_{i} \in \mathbb{R}^{d}\) and \(y_{i} \in\{-1,1\}\)
learn a classifier \(f(\boldsymbol{x})\) such that:

\[f\left(\boldsymbol{x}_{i}\right)= \begin{cases}>0, & \text { if } y_{i}=1 \\ <0, & \text { if } y_{i}=-1\end{cases}\]<div>
</div><div>Or: \(f\left(\boldsymbol{x}_{i}\right) y_{i}>0\) for a correct classification</div><div>E. g. if \(y_i = -1\), \(f(x_i) = 1\) would tell that the classification is incorrect.</div>
