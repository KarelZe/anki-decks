# Note
```
guid: pK(@b{sc|.
notetype: Basic-02d89-e0e22
```

### Tags
```
dl_cv::05_object_detection
```

## Front
What is the idea of ROI-Pooling? Why is it faster?

## Back
Instead of feeding each ROI to a ConvNet, we feed the image through
a ConvNet once and pass the feature-map along with the BBs of the
ROIs to the ROI-Pooling-Layer, which transforms each region into a
fixed-size box. <b>Visualization:</b> <img src="paste-6355614775f590c16a2b0cbdfd77b8c524a632e7.jpg">
