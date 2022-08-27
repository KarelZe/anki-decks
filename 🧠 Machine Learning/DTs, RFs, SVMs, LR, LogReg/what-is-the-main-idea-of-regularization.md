## Note
nid: 1629437832012
model: Basic-d7a3e-4ce08
tags: checklater, ml::01_linear_regression
markdown: false

### Front
What is the main idea of <b>regularization</b>?

### Back
Limit the model such that it can not fit the training data
perfectly anymore.
<div>
  One introduces a <b>regularization penalty</b> in cost function:
</div>
<div>
  \(E_{D}(\mathbf{w})+\lambda E_{W}(\mathbf{w}),\)
</div>
<div>
  where \(E_D\) is the error term from data, \(E_W\) is the
  regularization term and \(\lambda\) is the regularization factor.
</div>
