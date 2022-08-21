## Note
nid: 1652110356654
model: Basic-02d89
tags: 03_nn_basics_dlcv
markdown: false

### Front
Explain the problem of the <b>Internal Covariance Shift</b>.

### Back
<ul><li>The weights and biases are updated during <b>backprop</b></li><li>The input distribution at the <b>intermediate layers</b> shifts (-> ICS)</li><li>High learning rates are problematic, as the layers need to continously adapt to <b>large changes</b>.</li></ul>
