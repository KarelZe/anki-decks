# Note
```
guid: FRh]WT@(z[
notetype: Basic-02d89-e0e22
```

### Tags
```
dl_cv::04_deep_cnns_background
```

## Front
How can <b>CNNs</b> utilize <b>parallelism</b>?

## Back
<b>Data parallelism</b>
<ul>
  <li>Worker train the same model
  <li>Share gradients and adjust weights
  <li>Efficient when gradients are very sparse
</ul><b>Model parallelism</b>
<ul>
  <li>Workers train different parts of the model on the same data
  examples
  <li>Workers share neuron activations
</ul>
