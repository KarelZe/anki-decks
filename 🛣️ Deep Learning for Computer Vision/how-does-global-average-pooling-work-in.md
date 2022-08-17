## Note
nid: 1655107495025
model: Basic-02d89
tags: 05_dl_architectures_2_dl_cv
markdown: false

### Front
How does <b>Global Average Pooling</b> work in <b>GoogleNet</b>?

### Back
<ul><li>Average last feature maps to 1x1</li><li>One FC layer and softmax for classification</li><li>Global average pooling has 0 parameters, as only mean is calculated</li></ul><b>Visualization:</b>
<img src="paste-8e77ac16040357051eb762fa48c30a02b3e6ee82.jpg">
