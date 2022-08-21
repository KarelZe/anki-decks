## Note
nid: 1653325141246
model: Basic-02d89
tags: 04_dl_architectures_1_dl_cv
markdown: false

### Front
Why did <b>VGGNet</b> use smaller filters?

### Back
Stack of three 3x3 conv (stride 1) layers has same <b>effective
receptive field</b> as one 7x7 conv layer. Deeper more layer, mean
more non-linearities.
