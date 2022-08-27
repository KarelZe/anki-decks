## Note
nid: 1653672685734
model: Basic-02d89-e0e22
tags: bda::05_neural_networks
markdown: false

### Front
How is a <b>GRU</b> different from a <b>LSTM</b>?

### Back
<ul>
  <li>Cell state vectors represented by single vector \(h_t\)
  <li>Forget and input gate is fused in a single state controller
  <li>No output gate. Full state vector is output at every time
  step
  <li>New gate controller controls which part of previous state is
  shown to main layer
</ul>
