## Note
nid: 1563965221513
model: Basic-66395
tags: 
markdown: false

### Front
What is the idea of ROI-Pooling? Why is it faster? Why was it replaced?

### Back
Instead of feeding each ROI to a ConvNet, we feed the image through
a ConvNet once and pass the feature-map along with the BBs of the
ROIs to the ROI-Pooling-Layer, which transforms each region into a
fixed-size box.
<div>
  ROI-Pooling is replaced with ROI-Algin, because quantization is
  lossy.
</div>
