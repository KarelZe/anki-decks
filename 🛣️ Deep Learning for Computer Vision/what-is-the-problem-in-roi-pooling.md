# Note
```
guid: k>czA3Jmhr
notetype: Basic-02d89-e0e22
```

### Tags
```
dl_cv::07_image_seg
```

## Front
What is the <b>problem</b> in <b>ROI Pooling</b>?

## Back
It was not designed for <b>image segmentation</b>. Neural network
predicts float coordinates (x, y, width, height) ROI Pooling needs
integers however. Thus coordinates are quantized to integers, which
breakes the pixel-to-pixel alignment. <b>Visualization:</b>
<img src="paste-dc4e1fb246e9f60a953bc6a06ec72c845dcfdcb1.jpg">
