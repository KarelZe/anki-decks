## Note
nid: 1628960855046
model: Basic-d7a3e
tags: 08_svm, checklater, ultra
markdown: false

### Front
Explain how <b>sub-gradients</b> can be applied to SVMs for minimizing the <b>hinge loss</b> using <b>gradient descent</b>.

### Back
\[\operatorname{argmin}_{\mathbf{w}} \quad C
\underbrace{\sum_{i=1}^{N} \max \left(0,1-y_{i}
f\left(\boldsymbol{x}_{i}\right)\right)}_{\text {loss function
}}+\underbrace{\|\mathbf{w}\|^{2}}_{\text {regularization }}\]
<div>
  <div>
    <div>
      At each iteration, pick random training sample
      \(\left(\boldsymbol{x}_{i}, y_{i}\right)\)
    </div>
    <ul>
      <li>If \(y_{i} f\left(\boldsymbol{x}_{i}\right)<1: \quad
      \boldsymbol{w}_{t+1}=\boldsymbol{w}_{t}-\eta\left(2
      \boldsymbol{w}_{t}-C y_{i} \boldsymbol{x}_{i}\right)\)
      <li>Otherwise: \(\boldsymbol{w}_{t+1}=\boldsymbol{w}_{t}-\eta
      2 \boldsymbol{w}_{t} + 0\)
    </ul>
    <div>
      As subgradients of \(\max \left(0,1-y_{i}
      f\left(\mathbf{x}_{i}\right)\right)\) are:
    </div>
    <div><img src= 
    "paste-32f91c27bffa66c78bba9a3f73283b74dea8518d.jpg"></div>
  </div>
</div>
