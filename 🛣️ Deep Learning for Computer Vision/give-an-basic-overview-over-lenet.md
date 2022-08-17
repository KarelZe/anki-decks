## Note
nid: 1652602341247
model: Basic-02d89
tags: 04_deep_cnns_background
markdown: false

### Front
Give an <b>basic overview</b> over <b>LeNet</b>.

### Back
<ul>
  <li>Used for digit classification
  <li>Consists of Conv -> Pool -> conv -> Pool -> FC
  -> FC
  <li>Convolutional filters 5x5 applied at stride 1. Convolutional
  layers build up hierarchical filter structure
  <li>Subsampling / pooling increases robustness
  <li>Fully connected layers bring all information together,
  combines it once more.
  <li>Output layer with 10 classes, one for each digit
</ul><img src="paste-10c33c4920a7af82f70763ba6fca0cf25101c592.jpg">
