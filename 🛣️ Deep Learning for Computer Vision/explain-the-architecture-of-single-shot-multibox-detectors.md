# Note
```
guid: P5moZ~7CGc
notetype: Basic-02d89-e0e22
```

### Tags
```
dl_cv::05_object_detection
```

## Front
Explain the <b>architecture</b> of <b>Single Shot MultiBox
Detectors</b>?

## Back
Use detectors at varous stages with varying number of default
boxes. The SSD approach is based on a <b>feed-forward convolutional
network</b> that produces a <b>fixed-size collection of bounding
boxes and score</b>s for the presence of object class instances in
those boxes, followed by a <b>non-maximum suppression</b> step to
produce the final detections. The early network layers are based on
a standard architecture used for high-quality image classification
(truncated before any classification layers), which we will call
the base network e.g., VGG16. They then add auxiliary structure to
the network to produce detections. <b>Visualization:</b> <img src="paste-004d0ba45981c5873b1df95e8008088ac83a15bf.jpg">
