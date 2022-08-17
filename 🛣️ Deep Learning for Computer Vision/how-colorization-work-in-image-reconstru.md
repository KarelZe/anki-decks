## Note
nid: 1657443270259
model: Basic-02d89
tags: 10_video_self_learning
markdown: false

### Front
How colorization work in image reconstruction? What is the architecture? What is the loss?

### Back
<ul>
  <li>Similar to Autoencoders, but input is not the label
  <li>grayscale version of image is used as input, target is the
  original color image
  <li>network is forced to learn a meaningful representation to
  fill in the missing colors
  <li>Objective function can be rephrased to pixelwise
  classification task in order to prevent trivial outputs
</ul><b>Visualization:</b> <img src= 
"paste-41b67f43b2049c9faaa378a2682d184f44c4951d.jpg">
