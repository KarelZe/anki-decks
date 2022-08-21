## Note
nid: 1659869700015
model: Basic-02d89
tags: 12_adv_topics_dl_cv
markdown: false

### Front
Explain <b>few-shot segmentation</b> (One-way \(k\)-shot:).

### Back
Given \(k\) images + mask of one novel class, segment it. The
approach learns a condition branch in the training phase, so that a
given input image and a mask of outputs the weight for the
classifcation layer in the segmentation brnach. For training the
architecture, samples for few-shot tasks have to sampled from the
training data. <b>Visualization:</b> <img src= 
"paste-50bfb00f46b4ea2674999e3e6c14912312f7decd.jpg">
