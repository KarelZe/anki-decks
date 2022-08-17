## Note
nid: 1655132860830
model: Basic-02d89
tags: 05_object_detection_dl_cv
markdown: false

### Front
What is the <b>idea </b>behind <b>Mask R-CNN</b>?

### Back
Extension to Faster R-CNN by adding a branch for predicting segmentation masks on each Region of Interest (RoI), in parallel with the existing branch for classification and bounding box regression.

The mask branch is a small fully-connected network applied to each RoI, predicting a segmentation mask in a pixel-to-pixel manner.

<img src="paste-b1aef60b4bc7042f6ff34e887c72ff78528fae00.jpg">
