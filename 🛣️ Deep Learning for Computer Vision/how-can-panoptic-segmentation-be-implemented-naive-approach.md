# Note
```
guid: p5Nd]pAWq=
notetype: Basic-02d89-e0e22
```

### Tags
```
dl_cv::07_image_seg
```

## Front
How can <b>panoptic segmentation</b> be implemented? Naive
approach.

## Back
Heuristically combine outputs of <b>Semantic Segmentation</b> and
an <b>Instance Segmentation</b> model. The merging operation
prefers the Instance Segmentation masks over the Semantic
Segmentation maps and resolves mask overlaps. <b>Visualization:</b>
<img src="paste-1748514ffb38f8b9b8ea04134b8c0550791d5458.jpg">
