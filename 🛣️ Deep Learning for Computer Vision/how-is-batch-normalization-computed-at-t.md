## Note
nid: 1652101416334
model: Basic-02d89
tags: 03_nn_basics_dlcv
markdown: false

### Front
How is <b>batch normalization</b> computed at <b>test time</b>?

### Back
<ul><li>\(\mu_{k}\) and \(\sigma_{k}^{2}\) are <b>not computed</b> based on the batch</li><li>Use <b>fixed empirical mean and standard deviation</b> of the data computed during training.</li><li>The mean and standard deviation are <b>estimated during training with running averages</b>.</li></ul>
