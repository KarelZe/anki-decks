## Note
nid: 1628963405435
model: Basic-d7a3e-4ce08
tags: checklater, ml::08_svm
markdown: false

### Front
Consider a classifier \(f(x)\) and a class true class \(y_{i} \in\{-1,1\}\) and \(x_i\) a sample. Explain three different variants how points can contribute to the hinge loss of a SVM.

### Back
<div>
<div><ul>
<li>\(y_{i} f\left(\boldsymbol{x}_{i}\right)>1\): Point outside margin, no contribution to loss</li>
<li>\(y_{i} f\left(\boldsymbol{x}_{i}\right)=1\): Point is on the margin, no contribution to loss as in hard margin</li>
<li>\(y_{i} f\left(\boldsymbol{x}_{i}\right) \leq 1\): Point violates the margin, contributes to loss</li>
</ul>
</div></div>
