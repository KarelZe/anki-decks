## Note
nid: 1655144054410
model: Basic-02d89
tags: 05_object_detection_dl_cv
markdown: false

### Front
What is the idea of <b>Region Proposal Networks</b>?

### Back
<ul>
  <li>Take a mini net (RPN) and slide it over the feature map
  (stepsize 1)
  <li>At each position evaluate k different window sizes for
  objectness
  <li>Resulting in approx. W * H * k windows / proposals
</ul><b>Inputs:</b> Feature map from larger convolutional network
of size C x W x H <b>Output:</b> List of p proposals + "objectness"
score of size p x 6
