## Note
nid: 1655113369995
model: Basic-02d89-e0e22
tags: dl_cv::05_dl_architectures_2
markdown: false

### Front
Explain the <b>ResNet architecture</b>.

### Back
<ul>
  <li>Stack residual blocks
  <li>Every residual block has two 3x3 layers
  <li>Periodically double no. of filters and downsample by 2.
  <li>Additional conv layer at the beginning
  <li>No fully-connected layers at the end
  <li>Global average pooling at last convolution
</ul><b>Visualization</b>: <img src= 
"paste-6944a8a9f459ada3675dc174d2df984d8def2661.jpg">
