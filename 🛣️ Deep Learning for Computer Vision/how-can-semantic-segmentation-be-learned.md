## Note
nid: 1659870794372
model: Basic-02d89
tags: 12_adv_topics_dl_cv
markdown: false

### Front
How can semantic segmentation be learned from image labels. Explain the approach of Wei.

### Back
<ol><li>Train classifier on image level labels</li><li>Calcuate class activation maps and threshold them to determine most disciminative regions</li><li>Cut out these regions from the image</li><li>Re-train classifier on the "cut out training set"</li><li>Repeat, until classification deteriorates</li><li>Cut-out regions of each image make up ground truth segmentation masks</li></ol>
<b>Visualization:</b>
<img src="paste-2fef67de2a8b6b7fa7e54ebe0580473f3d60d653.jpg">
