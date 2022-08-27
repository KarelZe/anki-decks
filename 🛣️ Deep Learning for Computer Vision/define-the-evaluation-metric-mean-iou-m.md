## Note
nid: 1655715104616
model: Basic-02d89-e0e22
tags: dl_cv::07_image_seg
markdown: false

### Front
Define the evaluation metric <b>Mean IoU (Mean Intersection over
Union)</b>.

### Back
\(J(A, B)=\frac{|A \cap B|}{|A \cup B|}=\frac{T P}{T P+F P+F N}\)
Compare the prediction and target segmentation masks. Compute IoU
for each class and average results. <b>Visualization:</b> <img src= 
"paste-21e226b7e71485be2c424dd898156aee66a3cdee.jpg">
