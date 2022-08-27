## Note
nid: 1655109837152
model: Basic-02d89-e0e22
tags: dl_cv::05_dl_architectures_2
markdown: false

### Front
What is the idea behind the residual blocks of ResNet

### Back
Use network layers to fit a residual mapping instead of the direct
underlying mapping. Instead of learning the entire mapping \(H(x)\)
the residual between output and output is learned. That is, use
layers to fit residual \(F(x) = H(x) - x\) instead of \(H(x)\)
directly. <b>Visualization:</b> <img src= 
"paste-694948b4b8eee6c5e0b56828492b528782bbdc7b.jpg">
