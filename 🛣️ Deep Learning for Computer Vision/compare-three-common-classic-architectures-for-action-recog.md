# Note
```
guid: uJ$HPk+C$S
notetype: Basic-02d89-e0e22
```

### Tags
```
dl_cv::10_video_self_learning
```

## Front
Compare three <b>common, classic architectures</b> for <b>action
recognition</b>?

## Back
<b>ConvNet + LSTM (9M Parameters)</b>
<ul>
  <li>Underlying CNN for feature extraction: Inception-V1
  <li>LSTM with 512 hidden units (after the last AvgPool layer) +
  FC layer
  <li>Estimating the action from the resulting prediction Sequence:
  <ul>
    <li>Training: output at each time-step used for loss
    calculation
    <li>Testing: output of the last frame used for final prediction
  </ul>
  <li>Pre-trained on ImageNet
</ul><b>3D - ConvNet (79M Parameters)</b>
<ul>
  <li>Spatio-temporal filters, C3D architecture
  <li>High number of parameters -> harder to train
  <li>CNN Input: 16-frame snippets
  <li>Classification: score averaging over each snippet in the
  video
  <li>Trained from scratch
</ul><b>Two Stream CNN (12 M Parameters)</b>
<ul>
  <li>Underlying CNN for feature extraction: Inception-V1
  <li>Spatial (RGB) and Temporal (Optical Flow) streams trained
  separately
  <li>Prediction by score averaging
  <li>CNN Pre-trained on ImageNet
</ul><b>Viz:</b> <img src="paste-b8c13af2f8747056bddea348db5e66c0541ed7a9.jpg">
