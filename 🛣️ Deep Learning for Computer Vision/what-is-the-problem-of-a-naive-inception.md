## Note
nid: 1655106671248
model: Basic-02d89-e0e22
tags: dl_cv::05_dl_architectures_2
markdown: false

### Front
What is the <b>problem</b> of a <b>naive inception module</b>?

### Back
Very expensive to compute due to high number of parameters (854M ops for 28x28x256 input).

Pooling layer also preserves feature depth, which means total depth after concatenation can only grow at every layer.
