## Note
nid: 1652098222722
model: Basic-02d89
tags: 03_nn_basics_dlcv
markdown: false

### Front
What is the <b>intuition </b>behind <b>batch normalization</b>?

### Back
activations should have zero-mean and unit variance.

Therefore, each feature / channels is normalized using batch statistics. That is the mean and variance computed from the batch.

<b>Visualization:</b>
<img src="paste-56fa2573f989cc21e0356b65c99f320fa929f997.jpg">
