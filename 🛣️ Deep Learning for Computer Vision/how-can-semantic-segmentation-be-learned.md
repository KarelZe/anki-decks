## Note
nid: 1659870794372
model: Basic-02d89-e0e22
tags: dl_cv::12_adv_topics
markdown: false

### Front
How can semantic segmentation be learned from image labels. Explain the approach of Wei.

### Back
<ol>
  <li>Train classifier on image level labels
  <li>Calcuate class activation maps and threshold them to
  determine most disciminative regions
  <li>Cut out these regions from the image
  <li>Re-train classifier on the "cut out training set"
  <li>Repeat, until classification deteriorates
  <li>Cut-out regions of each image make up ground truth
  segmentation masks
</ol><b>Visualization:</b> <img src= 
"paste-2fef67de2a8b6b7fa7e54ebe0580473f3d60d653.jpg">
