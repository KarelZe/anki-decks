## Note
nid: 1651480350288
model: Basic-02d89
tags: 02_basics_nn_dlcv
markdown: false

### Front
What are the <b>drawbacks </b>of the <b>Sigmoid function</b>?

### Back
<ul>
  <li><b>Vanishing gradients:</b> functions gradient at either tail
  of 1 or 0 is almost zero
  <li>Outputs are not <b>zero-centered</b>, which is undesirable
  since the input data is often not zero-centered. If the input is
  always positive, the weight gradients will become either all
  positive or negative resulting in zig-zagging dynamics.
</ul>
