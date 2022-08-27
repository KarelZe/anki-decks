## Note
nid: 1653673543901
model: Basic-02d89-e0e22
tags: bda::05_neural_networks
markdown: false

### Front
Explain the <b>basic components</b> of a <b>GRU</b>.

### Back
<img src="paste-17111a79d52081a91a29c950071383aa6715e14c.jpg">
<ul>
  <li>Cell state is reperesented in a single vector \(h_t\).
  <li>Single state controller controls fuses forget and input gate,
  with 1 input gate is open and forget is closed and 0 opposite
  happens. Whenever memory must be stored, the location where it
  will be stored is erased first.
  <li>No output gate. Full state vector is revealed.
</ul><b>Equations:</b> \(z_{t}=\sigma\left(W_{x z}^{\mathrm{T}}
\cdot x_{t}+W_{h z}^{\mathrm{T}} \cdot h_{t-1}\right)\)
\(r_{t}=\sigma\left(W_{x r}^{\mathrm{T}} \cdot x_{t}+W_{h
r}^{\mathrm{T}} \cdot h_{t-1}\right)\) \(g_{t}=\tanh \left(W_{x
g}^{\mathrm{T}} \cdot x_{t}+W_{h g}^{\mathrm{T}} \cdot
h_{t-1}+b_{g}\right)\) \(h_{t}=\left(1-z_{t}\right) \otimes
h_{t-1}+z_{t} \otimes g_{t}\)
