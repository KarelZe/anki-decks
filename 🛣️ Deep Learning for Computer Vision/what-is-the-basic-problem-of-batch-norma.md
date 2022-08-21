## Note
nid: 1652098589315
model: Basic-02d89
tags: 03_nn_basics_dlcv
markdown: false

### Front
What is the <b>basic problem</b> of <b>batch normalization</b>?

### Back
<b>Batch normalization</b> aims for zero-mean <b>unit-variance
activations</b>. Forcing the activations to be strictly 0 mean and
unit variance can limit the expressive power of the network.
<b>Solution:</b> Allow the network to learn parameters \(\gamma\)
and \(\beta\) that can rescale the normalized output to any value
that the network desires.
