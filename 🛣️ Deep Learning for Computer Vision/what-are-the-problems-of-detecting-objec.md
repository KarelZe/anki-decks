## Note
nid: 1653288254296
model: Basic-02d89-e0e22
tags: dl_cv::05_object_detection
markdown: false

### Front
What are the problems of <b>detecting objects</b> using a
<b>sliding window</b>?

### Back
<ul>
  <li>only a <b>small part of the image</b> is checked and then
  classified
  <li>objects in image can be of <b>variable size</b>. This
  requires different scales
  <li>Classifiying image patches with different locations and
  scales is <b>time consuming</b>
</ul>
