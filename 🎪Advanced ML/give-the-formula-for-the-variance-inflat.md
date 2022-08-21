## Note
nid: 1619965290291
model: Basic-b122e
tags: 03_vorlesung
markdown: false

### Front
Give the formula for the <b>variance inflation vector (VIF)</b>.

### Back
\[\text{VIF}=\frac{1}{\left(1-R_{j}^{2}\right)},\]<div>
</div><div>where \(j\)-th variable is regressed on the remaining \(k-1\) variables. the resulting regession would look like:</div><div>\(x_{j}=c+b_{1}^{(j)} x_{1}+\cdots+b_{j-1}^{(j)} x_{j-1}+b_{j+1}^{(j)} x_{j+1}+\cdots+b_{k}^{(j)} x_{k} \quad j=1,2, \cdots, k\)
</div><div>
</div><div>Then we obtain coefficients of determination of this regression, \(R^2_j\).</div>
