# Note
```
guid: yJzB~EkBaA
notetype: Basic-02d89-e0e22
```

### Tags
```
dl_cv::03_nn_basics
```

## Front
How is <b>batch normalization</b> computed at <b>test time</b>?

## Back
<ul>
  <li>\(\mu_{k}\) and \(\sigma_{k}^{2}\) are <b>not computed</b>
  based on the batch
  <li>Use <b>fixed empirical mean and standard deviation</b> of the
  data computed during training.
  <li>The mean and standard deviation are <b>estimated during
  training with running averages</b>.
</ul>
