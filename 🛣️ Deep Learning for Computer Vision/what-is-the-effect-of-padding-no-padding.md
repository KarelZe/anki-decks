# Note
```
guid: O-Tp%7qMO(
notetype: Basic-02d89-e0e22
```

### Tags
```
dl_cv::04_deep_cnns_background
```

## Front
What is the effect of <b>padding / no padding</b>?

## Back
<b>No padding:</b>
<ul>
  <li>Filter cannot be evaluated at the corner pixel due to missing
  neighborhood
  <li>Output shape is smaller than input shape
</ul><img src="paste-49288b70253087a7583773be73191aa2fd6b1ebe.jpg">
<b>Padding:</b>
<ul>
  <li>Filter can be evaluated at the corner pixel
  <li>Output shape will be the same size given approproiate padding
  size
</ul><img src="paste-de04e75a3bf16f5715a3ba06f34c0e00032b238b.jpg">
