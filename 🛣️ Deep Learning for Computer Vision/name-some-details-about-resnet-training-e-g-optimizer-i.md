# Note
```
guid: Fv3^A/{oET
notetype: Basic-02d89-e0e22
```

### Tags
```
dl_cv::05_dl_architectures_2
```

## Front
Name some details about <b>ResNet</b> training (e. g., optimizer,
initialization, drop-out)

## Back
<ul>
  <li>Batch normalization after every convolutional layer
  <li>Xavier initialization
  <li>SGD + Momentum (0.9)
  <li>Learning rate: 0.1 divided by 10 when validation error
  plateaus
  <li>No drop-out
</ul>
