## Note
nid: 1653714035612
model: Basic-02d89-e0e22
tags: bda::02_classification
markdown: false

### Front
How does <b>training</b> a <b>stacking classifier</b> work?

### Back
<ul>
  <li>Training set is split into two (three) subsets
  <li>Train set is used to train predictors
  <li>Predictions are made on holdout set
  <li>Meta classifier is trained on prediction set
  <li>Meta classifier tested on test set.
</ul><b>Visualization:</b> <img src= 
"paste-3a3937a6f3a2f9249236287f650902826f737014.jpg">
