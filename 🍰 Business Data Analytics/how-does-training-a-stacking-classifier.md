## Note
nid: 1653714035612
model: Basic-02d89
tags: 02_classification_bda
markdown: false

### Front
How does <b>training</b> a <b>stacking classifier</b> work?

### Back
<ul><li>Training set is split into two (three) subsets</li><li>Train set is used to train predictors</li><li>Predictions are made on holdout set</li><li>Meta classifier is trained on prediction set</li><li>Meta classifier tested on test set.</li></ul><b>Visualization:</b>
<img src="paste-3a3937a6f3a2f9249236287f650902826f737014.jpg">
