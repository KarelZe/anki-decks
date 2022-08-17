## Note
nid: 1653326085260
model: Basic-02d89
tags: 04_dl_architectures_1_dl_cv
markdown: false

### Front
What is the effective receptive field of three 3x3 conv (stride 1)
layers in <b>VGGNet</b>?

### Back
Fewer parameters: 3*(3^2 M) * C Vs
1 * (7^2 M) * C for M input channels per layer and C kernels per layer
