## Note
nid: 1655105075010
model: Basic-02d89
tags: 05_dl_architectures_2_dl_cv
markdown: false

### Front
What is the <b>idea </b>behind <b>DeCAF</b>?

### Back
<ul>
  <li>Train network end-to-end on image classification (e. g.,
  ImageNet)
  <li>Use pre-trained network for:
  <ul>
    <li><b>classification</b> (switch last layer for new task;
    re-run training for few epochs)
    <li><b>feature extractor</b> (remove last layer, use hidden
    unit as feature for e. g., SVM)
  </ul>
</ul><b>Visualization:</b> <img src= 
"paste-91e847b3d9b05e2c335b3b94b877bad5cc292a64.jpg">
