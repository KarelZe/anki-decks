## Note
nid: 1651480747830
model: Basic-02d89
tags: 02_basics_nn_dlcv
markdown: false

### Front
What are the <b>drawbacks</b> of <b>ReLU</b>?

### Back
<ul>
  <li>Large gradient flow could cause the weights to update in such
  away that the neuron will never activate again
  <li>If this happens, the gradient flowing throught the unit will
  forever be zero from that point on.
</ul>
