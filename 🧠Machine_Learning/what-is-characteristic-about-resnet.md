## Note
nid: 1629295630032
model: Basic-d7a3e
tags: 11_rnns
markdown: false

### Front
What is characteristic about <b>ResNet</b>?

### Back
<div>
  <div>
    <ul>
      <li>152-layer model for ImageNet
      <li>Uses so-called residual blocks / layers
      <li>Every residual block has two 3x3 convolutional layer
      <li>Periodically, double # of filters and downsample
      spatially using stride 2 (/2 in each dimension)
      <li>Additional convolutional layer at the beginning
      <li>No Fully-Connected layers at the end (only FC 1000 to
      output classes)
      <li>For deeper networks (ResNet-50+) use "bottleneck" layer
      to improve efficiency
    </ul>
    <div><img src= 
    "paste-cae52d4bc93e36739c26476b7256984ff7e4c919.jpg"></div>
  </div>
</div>
