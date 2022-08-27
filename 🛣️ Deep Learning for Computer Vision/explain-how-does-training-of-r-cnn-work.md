## Note
nid: 1655134766047
model: Basic-02d89-e0e22
tags: dl_cv::05_object_detection
markdown: false

### Front
Explain how does training of R-CNN work?

### Back
Gradients can backpropagate into feature layers through ROI pooling
layers (just as with normal maxpool layers). They use a
<b>multi-task loss</b> \(L\) on each labeled RoI to jointly train
for classification and bounding-box regression: \[ L\left(p, u,
t^{u}, v\right)=L_{\mathrm{cls}}(p, u)+\lambda[u \geq 1]
L_{\mathrm{loc}}\left(t^{u}, v\right), \] in which
\(L_{\mathrm{cls}}(p, u)=-\log p_{u}\) is log loss for true class
\(u\). The second task loss, \(L_{\text {loc }}\), is defined over
a tuple of true bounding-box regression targets for class \(u, v=\)
\(\left(v_{\mathrm{x}}, v_{\mathrm{y}}, v_{\mathrm{w}},
v_{\mathrm{h}}\right)\), and a predicted tuple
\(t^{u}=\left(t_{\mathrm{x}}^{u}, t_{\mathrm{y}}^{u},
t_{\mathrm{w}}^{u}, t_{\mathrm{h}}^{u}\right)\), again for class
\(u\). <b>Visualization</b>: <img src= 
"paste-eafb9e3e922841c9afb407e211a0a43f0d00a326.jpg">
