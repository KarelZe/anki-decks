## Note
nid: 1655108965353
model: Basic-02d89
tags: 05_dl_architectures_2_dl_cv
markdown: false

### Front
What is the <b>idea </b>behind <b>auxilary loss layers</b> in <b>GoogleNet</b>?

### Back
<ul><li>Inject additional gradient at lower layers(Avg. Pool, 1x1 Conv., Fully-connected, Fully-connected, Softmax).</li><li>Encourage discrimation in the lower stages through the auxiliary loss layers, which increases the gradient signal that get propagated back.</li><li>During training the loss gets added to the total loss of the network with discount weight.</li><li>Diabled at inference time. Take results at very end.</li></ul><b>Visualization</b>:
<img src="paste-8a665e5f6a7cbf5a40c9bc25b25fad26c64e2c55.jpg">
