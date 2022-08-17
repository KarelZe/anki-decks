## Note
nid: 1653200809204
model: Basic-02d89
tags: 06_trainining_tuning_bda
markdown: false

### Front
What drives the <b>vanishing / exploding gradients</b>?

### Back
Combination of sigmoid activation function and random intialization with standardnormal distribution drives the issue.

Variance increases at each layer until activation function "saturates" at the network's top layers.
