## Note
nid: 1655107011060
model: Basic-02d89-e0e22
tags: dl_cv::05_dl_architectures_2
markdown: false

### Front
What is the solution to high computational complexity of naive inception modules?

### Back
"bootleneck" layers that use 1x1 convolution to reduce feature
depth. <b>Visualization:</b> Preserve size (eq. to pixel), but
reduce the depth (eq. no. of feature maps) similar to a
dimensionality reduction. <img src= 
"paste-16ba71db42545d050d4fda1bdf80d821d7432d14.jpg">
<b>Comparsion:</b> <img src= 
"paste-81b217034d2b6fcbd4f2cf2f45d2a84b47269f79.jpg">
