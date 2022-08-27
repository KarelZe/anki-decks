## Note
nid: 1655735309422
model: Basic-02d89-e0e22
tags: dl_cv::07_image_seg
markdown: false

### Front
Define the <b>loss</b> of <b>Mask R-CNN</b>. What are its
components?

### Back
\(L = L_{\text {cls }} + L_{\text {box}} + L_{\text {mask}}\)

With:
\(L_{\text {cls }}\) - classification loss, sigmoid cross. Entropy - as in R-CNN
\(L_{\text {box }}\) - difference between GT and outp. coordinates - as in R-CNN
\(L_{\text {mask }}-\) sigmoid cross. Entropy between GT and prediction (not softmax)
