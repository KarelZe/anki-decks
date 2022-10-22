# Note
```
guid: OkXxmanWcZ
notetype: Basic-02d89-e0e22
```

### Tags
```
dl_cv::10_video_self_learning
```

## Front
Explain what <b>P-CNN</b> is.

## Back
Pose based CNN features for action recognition. Extract appearance
and motion CNN descriptors for each frame and aggregate over time
to form a video descriptor Construct P-CNN features
<ul>
  <li>Appearance feature from RGB frame
  <li>Motion features from estimated optical flow frame
  \(\left(v_{x}, v_{y}\right.\), magnitude
  <li>Given a video frame and corresponding body joints, crop RGB
  and flow patches to input to two CNN
</ul>The output of \(2^{\text {nd }}\) fully connected layer is
used as frame descriptor \(f_{t}{ }^{p}\) descriptor \(f_{t}^{p}\)
for each part \(p\) and frame \(t\) are aggregated for
\(\mathrm{T}\) frames using \(\min\) and \(\max\) <b>Viz:</b>
<img src="paste-52c864e7fdfd2046d81ad526a91c7c23103c5cc4.jpg">
