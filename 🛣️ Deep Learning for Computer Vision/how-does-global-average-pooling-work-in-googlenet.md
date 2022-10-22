# Note
```
guid: K*nvH`9H1=
notetype: Basic-02d89-e0e22
```

### Tags
```
dl_cv::05_dl_architectures_2
```

## Front
How does <b>Global Average Pooling</b> work in <b>GoogleNet</b>?

## Back
<ul>
  <li>Average last feature maps to 1x1
  <li>One FC layer and softmax for classification
  <li>Global average pooling has 0 parameters, as only mean is
  calculated
</ul><b>Visualization:</b> <img src="paste-8e77ac16040357051eb762fa48c30a02b3e6ee82.jpg">
