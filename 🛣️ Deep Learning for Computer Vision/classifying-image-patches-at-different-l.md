## Note
nid: 1653296343371
model: Basic-02d89-e0e22
tags: dl_cv::05_object_detection
markdown: false

### Front
Classifying image patches at different locations and scales is time consuming. How can this problem be tackled?

### Back
<ul>
  <li>Use a very fast classifier (e. g. HOG, DPM)
  <li>Run the classifier only on some locations and scales (i. e.
  region proposals)
</ul>
