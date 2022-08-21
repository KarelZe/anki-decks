## Note
nid: 1629188479349
model: Basic-d7a3e
tags: 10_neural_networks, checklater
markdown: false

### Front
Explain how one can use the following computational graph to
calculate the derivatives. Note them down in a simplified notation
/ as error signals.
<div><img src=
"paste-c0368e2f12364c4b2f4628f6c39483c989496ce5.jpg"></div>
<div>
  <b>Forward pass:</b>
</div>
<div>
  \(z=w x+b\) \(y=\sigma(z)\) \(\mathcal{L}=\frac{1}{2}(y-t)^{2}\)
</div>

### Back
<div><b>Backward pass:</b></div><div>
</div>\(\bar{y}=y-t\)
\(\bar{z}=\bar{y} \sigma^{\prime}(z)\)
\(\bar{w}=\bar{z} x\)
\(\bar{b}=\bar{z}\)
