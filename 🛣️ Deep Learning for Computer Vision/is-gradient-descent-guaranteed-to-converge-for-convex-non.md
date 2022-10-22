# Note
```
guid: yv4jLl<N34
notetype: Basic-02d89-e0e22
```

### Tags
```
dl_cv::02_basics_nn
```

## Front
Is Gradient Descent guaranteed to converge for convex / non-convex loss functions?

## Back
GD will certainly (Batch GD) or almost certainly (Mini-Batch GD)
converge to the <b>global minimum</b> for <b>convex</b> error
surfaces and to a <b>local minimum for non-convex</b> surfaces.
