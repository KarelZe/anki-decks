## Note
nid: 1655734832294
model: Basic-02d89
tags: 07_image_seg_dl_cv
markdown: false

### Front
What is the <b>problem</b> in <b>ROI Pooling</b>?

### Back
It was not designed for <b>image segmentation</b>. Neural network predicts float coordinates (x, y, width, height)
ROI Pooling needs integers however. Thus coordinates are quantized to integers, which breakes the pixel-to-pixel alignment.

<b>Visualization:</b>
<img src="paste-dc4e1fb246e9f60a953bc6a06ec72c845dcfdcb1.jpg">
