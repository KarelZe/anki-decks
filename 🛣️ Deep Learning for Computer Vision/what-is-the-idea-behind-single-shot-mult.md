## Note
nid: 1655131665471
model: Basic-02d89
tags: 05_object_detection_dl_cv
markdown: false

### Front
What is the idea behind <b>Single Shot MultiBox Detectors</b>?

### Back
<ul>
  <li>Use a set of fixed size default boxes at each position in a
  feature map (similar to anchors)
  <li>Classify object class and box regressions for each default
  box
  <li>Apply boxes at different layers in the ConvNet with layers of
  different sizes.
</ul><b>Visualization:</b> <img src= 
"paste-24af24a155089f8b33258b4fdc4213fcc95217f6.jpg">
