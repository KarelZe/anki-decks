# Note
```
guid: E#JAoa1XDx
notetype: Basic-02d89-e0e22
```

### Tags
```
dl_cv::07_image_seg
```

## Front
Explain <b>Deeplab</b> form <b>image segmentation</b>.

## Back
<ul>
  <li>Apply atrous (dilated) convolution
  <ul>
    <li>Explicit control of the resolution at which feature
    responses are computed
    <li>Enlarge field of view with the same number of parameters
  </ul>
  <li>Feature aggregation through atrous spatial pyramid pooling
  <li>Potential postprocessing with fully connected Conditional
  Random Fields (CRF) to improve localization performance
</ul><b>Visualization:</b> <img src="paste-9a5263670c10cb3ada27d1d65b24e14fdd7bdddb.jpg">
