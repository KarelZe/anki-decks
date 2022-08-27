## Note
nid: 1607185371332
model: Basic-d7a3e-4ce08
tags: ml::04_trees_rf
markdown: false

### Front
<p>Was ist ein <b>gängiges Splitkriterium</b> für <b>Classification
Trees</b>?

### Back
<p><b>Minimum Entropy</b>
<p>\[\text { score }=N_{L} H\left(p_{\mathrm{L}}\right)+N_{R}
H\left(p_{\mathrm{R}}\right),\]
<p>wobei \(H\left(p_{L}\right)=-\sum_{k} p_{L}(k) \log p_{L}(k)\)
die Entropie im linken Teilbaum ist. \(N_{L}\) sind die Samples im
linken Teilbaum.
