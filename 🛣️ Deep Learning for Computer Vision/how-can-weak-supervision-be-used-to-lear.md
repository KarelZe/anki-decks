## Note
nid: 1659870598892
model: Basic-02d89
tags: 12_adv_topics_dl_cv
markdown: false

### Front
How can weak <b>supervision </b>be used to learn <b>bounding boxes</b>? Explain the approach of Khoreva.

### Back
Assign each pixel its bounding-box class
Train a segmentation model
Create new ground truths:
<ul><li>Using the segmentation model</li><li>Pixels outside bounding-boxes are reset to background</li><li>Use bounding-box pixels, if too few pixels are labeled (object extend prior)</li><li>Boundary aware filtering (DenseCRF)</li></ul>Repeat the process iteratively

<b>Visualization:</b>
