## Note
nid: 1659870598892
model: Basic-02d89-e0e22
tags: dl_cv::12_adv_topics
markdown: false

### Front
How can weak <b>supervision</b> be used to learn <b>bounding
boxes</b>? Explain the approach of Khoreva.

### Back
Assign each pixel its bounding-box class Train a segmentation model
Create new ground truths:
<ul>
  <li>Using the segmentation model
  <li>Pixels outside bounding-boxes are reset to background
  <li>Use bounding-box pixels, if too few pixels are labeled
  (object extend prior)
  <li>Boundary aware filtering (DenseCRF)
</ul>Repeat the process iteratively <b>Visualization:</b>
