## Note
nid: 1629024144763
model: Basic-d7a3e
tags: 08_svm, checklater
markdown: false

### Front
How can one calculate the width of the <b>margin</b> of a SVM?

### Back
Note that \(\mathbf{w}^{T} \mathbf{x}+b=0\) and
\(c\left(\mathbf{w}^{T} \mathbf{x}+b\right)=0\) define the same
hyperplane.
<div>
  That means \(c\) can be chosen freely.
</div>
<div>
  For positive support vectors we set
</div>
<div>
  \(\mathbf{w}^{T} \mathbf{x}_{+}+b=+1\)
</div>
<div>
  For negative support vectors
</div>
<div>
  \(\mathbf{w}^{T} \mathbf{x}_{-}+b=-1\)
</div>
<div>
  The margin is given by:
</div>
<div>
  \(\frac{\mathbf{w}^{T}
  \mathbf{x}_{+}+b}{\|\mathbf{w}\|}-\frac{\mathbf{w}^{T}
  \mathbf{x}_{-}+b}{\|\mathbf{w}\|}=\frac{2}{\|\mathbf{w}\|}\)
</div>
