## Note
nid: 1655110733417
model: Basic-02d89
tags: 05_dl_architectures_2_dl_cv
markdown: false

### Front
Name some details about <b>ResNet</b> training (e. g., optimizer,
initialization, drop-out)

### Back
<ul>
  <li>Batch normalization after every convolutional layer
  <li>Xavier initialization
  <li>SGD + Momentum (0.9)
  <li>Learning rate: 0.1 divided by 10 when validation error
  plateaus
  <li>No drop-out
</ul>
