## Note
nid: 1655134296841
model: Basic-02d89
tags: 05_object_detection_dl_cv
markdown: false

### Front
Give an <b>overview </b>over the <b>Fast R-CNN architecture</b>.

### Back
<ul>
  <li>An input image and multiple regions of interest (RoIs) are
  input into a fully convolutional network.
  <li>Each RoI is pooled into a fixed-size feature map and then
  mapped to a feature vector by fully connected layers (FCs).
  Feature map is computed once per proposal.
  <li>The network has two output vectors per RoI: softmax
  probabilities and per-class bounding-box regression offsets.
  <li>The architecture is trained end-to-end with a multi-task loss
</ul><b>Visualization:</b> <img src= 
"paste-98e809ffd8bccbb1fb88ac7bf713219c2d9542cf.jpg">
