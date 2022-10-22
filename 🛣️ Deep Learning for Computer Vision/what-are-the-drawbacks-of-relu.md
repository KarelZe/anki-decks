# Note
```
guid: stbFVW&i&>
notetype: Basic-02d89-e0e22
```

### Tags
```
dl_cv::02_basics_nn
```

## Front
What are the <b>drawbacks</b> of <b>ReLU</b>?

## Back
<ul>
  <li>Large gradient flow could cause the weights to update in such
  away that the neuron will never activate again
  <li>If this happens, the gradient flowing throught the unit will
  forever be zero from that point on.
</ul>
