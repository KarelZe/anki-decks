## Note
nid: 1657443512862
model: Basic-02d89
tags: 10_video_self_learning
markdown: false

### Front
Explain how the prediction of context and position works in self-supervised learning.

### Back
<ul><li>Every image has inherent structure that can be used for self-supervised training: context and position.</li><li>One samples 2 image crops from a \(3 \times 3\) grid and try to predict the position of the second crop.</li><li>Formulated as a 8 class classificatio nproblem.</li></ul>
<b>Visualization:</b>
<img src="paste-01635d56ea985cddc33a0ade9f008189f8f689c9.jpg">
