## Note
nid: 1620231599896
model: Basic-d7a3e-4ce08
tags: 04_vorlesung
markdown: false

### Front
Use the following table to predict the probabilty of default using
a logistic regression model.
<div>
  Aussume a credit card balance of $ 1,000.
  <div>
    <div><img src= 
    "paste-7c799490c296454312fc610cdaf75f32775afe19.jpg"></div>
  </div>
</div>

### Back
The probability of default for an indivual with balance of $1,000
is:
<div>
  \[\hat{p}(X)=\frac{e^{\hat{\beta}_{0}+\hat{\beta}_{1}
  X}}{1+e^{\hat{\beta}_{0}+\hat{\beta}_{1}
  X}}=\frac{e^{-10.6513+0.0055 \times 1,000}}{1+e^{-10.6513+0.0055
  \times 1,000}}=0.00576\]
</div>
