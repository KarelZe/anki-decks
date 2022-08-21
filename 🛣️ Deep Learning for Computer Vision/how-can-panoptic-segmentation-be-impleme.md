## Note
nid: 1655716105717
model: Basic-02d89
tags: 07_image_seg_dl_cv
markdown: false

### Front
How can <b>panoptic segmentation</b> be implemented? Naive
approach.

### Back
Heuristically combine outputs of <b>Semantic Segmentation</b> and
an <b>Instance Segmentation</b> model. The merging operation
prefers the Instance Segmentation masks over the Semantic
Segmentation maps and resolves mask overlaps. <b>Visualization:</b>
<img src="paste-1748514ffb38f8b9b8ea04134b8c0550791d5458.jpg">
