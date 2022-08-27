## Note
nid: 1629197746858
model: Basic-d7a3e-4ce08
tags: ml::10_neural_networks
markdown: false

### Front
Explain how changing the learning rate \(\eta\) using <b>Cosine</b>
works.

### Back
\(\alpha_{t}=\frac{1}{2} \alpha_{0}(1+\cos (t \pi / T))\)
<div>
  where \(\alpha_{0}\) is the initial learning rate,
  \(\alpha_{t}:\) Learning rate at epoch t and \(T:\) Total number
  of epochs.
  <div><img src=
  "paste-5b0cf9d2d13ce4b605af6ad161ad868e3e04a5c2.jpg"></div>
</div>
