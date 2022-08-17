## Note
nid: 1655732895133
model: Basic-02d89
tags: 07_image_seg_dl_cv
markdown: false

### Front
Explain the <b>inner workings</b> of a <b>Multi-task Network
Cascade</b>.

### Back
<b>Regressing Box-level Instances</b>
<ul>
  <li>Input: shared convolutional features, Output: set of boxes
  <li>Model includes a \(3 \times 3\) convolutional layer and two
  \(1 \times 1\) layers
  <li>The first \(1 \times 1\) convolutional layer predicts the box
  location \(\left(k \times 4\right.\) coordinates per pixel)
  <li>The second output layer classifies the box to
  object/non-object
</ul><b>Regressing Mask-level Instances</b>
<ul>
  <li>Input: convolutional features and bboxes, Output: pixelwise
  Instance-Masks
  <li>Each bbox is fed into the model individually
  <li>Features of size \(14 \times 14\) are extracted from each
  bbox
  <li>Note: the pixelwise instance-masks are still class agnostic
</ul><b>Categorizing Instances</b>
<ul>
  <li>Input: convolutional features and masks, Output:
  instance-aware sem. Segm.
  <li>Outputs category scores for each instance
  <li>The convolutional features are masked out from the stage-2
  masks
  <li>The masked out features are used on 2 fully connected layers
  <li>The output layer is \(C\) dimensional for each proposal (C =
  number classes)
</ul><b>Visualization:</b> <img src= 
"paste-9c7993142b52d0103c3813fb6e1538bd8250965f.jpg">
