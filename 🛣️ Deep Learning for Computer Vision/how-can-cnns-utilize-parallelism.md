## Note
nid: 1652598101588
model: Basic-02d89
tags: 04_deep_cnns_background
markdown: false

### Front
How can <b>CNNs</b> utilize <b>parallelism</b>?

### Back
<b>Data parallelism</b>
<ul><li>Worker train the same model</li><li>Share gradients and adjust weights</li><li>Efficient when gradients are very sparse</li></ul><b>Model parallelism</b>
<ul><li>Workers train different parts of the model on the same data examples</li><li>Workers share neuron activations</li></ul>
