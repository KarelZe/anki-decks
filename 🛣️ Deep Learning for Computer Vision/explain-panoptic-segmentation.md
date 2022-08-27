## Note
nid: 1655715764114
model: Basic-02d89-e0e22
tags: dl_cv::07_image_seg
markdown: false

### Front
Explain <b>panoptic segmentation</b>?

### Back
Fuses semantic segmentation, where every pixel gets a label and
insance segmentation, that assigns a mask and a label to each
object. The task differentiates between stuff (everything that is
not countable) and things (everything that can be counted). Stuff
receives a default id, but eacht thing receives a unique id besides
the class label. <b>Visualization:</b> <img src= 
"paste-248b744e83fa74fd14fd0a322a1ac2c3a4628f87.jpg">
