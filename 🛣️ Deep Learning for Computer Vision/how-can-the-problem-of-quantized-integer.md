## Note
nid: 1655735046508
model: Basic-02d89-e0e22
tags: dl_cv::07_image_seg
markdown: false

### Front
How can the problem of <b>quantized integers</b> be solved in
<b>ROI Pooling</b>?

### Back
Using <b>ROI Align</b>.
<ul>
  <li>Use bilinear interpolation instead of quantization of coords.
  <li>Split input feature map into \(H\times\) bins.
  <li>For each bin set 4 points at regular intervals from each
  other Bilinear interpolate pixels for each of the 4 points in
  each bin
  <li>Final result obtained by max or avg pooling of the 4 points.
</ul><b>Visualization:</b> <img src= 
"paste-8b0b246a3168c31dc46ec8599de8dae5e24f054e.jpg">
