## Note
nid: 1653298990720
model: Basic-02d89
tags: 05_object_detection_dl_cv
markdown: false

### Front
Explain the <b>training</b> of the <b>R-CNN</b>.

### Back
<ol>
  <li>Train AlexNet on ImageNet (1000 classes)
  <li>Reinitialize last layers to a different dimension (depending
  on the number of classes of the new classifier) and train a new
  model
  <li>Train a classifier e. g., binary SVM for each object class
  <li>Improve region proposal using a regression model to improve
  the estimate of the location with features of region as input and
  bounding box coordinates as output
</ol><img src="paste-525659562d65be0d80d438fdf5dfd35d85f42afa.jpg">
<img src="paste-debf935afca1d20833073196be2f977b93d952dc.jpg">
<img src="paste-19697750c7acd36e2fc79643a8278fc9866a03f1.jpg">
