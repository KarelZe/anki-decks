## Note
nid: 1607452837611
model: Basic-d7a3e-4ce08
tags: checklater, ml::02_linear_classification
markdown: false

### Front
<p>Wie sieht die Softmax Likelihood function für einen Multiclass
Klassifizierer aus?

### Back
<p><b>Softmax Likelihood function:</b>
<p>\(p(c=i \mid \boldsymbol{x})=\frac{\exp
\left(\boldsymbol{w}_{i}^{T}
\boldsymbol{\phi}(\boldsymbol{x})\right)}{\sum_{k=1}^{K} \exp
\left(\boldsymbol{w}_{k}^{T}
\boldsymbol{\phi}(\boldsymbol{x})\right)}\)
<div>
  <div>
    <ul>
      <li>Each class gets a weight vector
      <li>Higher probability for class \(i\) if
      \(\boldsymbol{w}_{i}^{T} \phi(\boldsymbol{x})\) is high
      <li>For \(K=2, \boldsymbol{w}_{2}\) is redundant → better to
      use sigmoid
    </ul>
    <div><img src= 
    "paste-39842fc139de6141d2ecc902cc9326fa3e04220c.jpg"></div>
  </div>
</div>
