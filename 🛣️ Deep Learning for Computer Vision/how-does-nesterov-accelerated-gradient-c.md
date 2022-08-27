## Note
nid: 1651480068977
model: Basic-02d89-e0e22
tags: dl_cv::02_basics_nn
markdown: false

### Front
How does <b>Nesterov accelerated gradient</b> compare to
<b>Momentum</b>?

### Back
Modification of the Momentum update. Instead of computing gradient
at the current position (red dot), calculate the gradient at the
future approximate position (green arrow head) and then update.
<b>Visualization:</b> <img src= 
"paste-2cdf42feaad797c9fbf0ec5b889e0c557c68c1de.jpg">
