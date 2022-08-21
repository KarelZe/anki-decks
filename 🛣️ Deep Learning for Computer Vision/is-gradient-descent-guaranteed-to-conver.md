## Note
nid: 1651477605010
model: Basic-02d89
tags: 02_basics_nn_dlcv
markdown: false

### Front
Is Gradient Descent guaranteed to converge for convex / non-convex loss functions?

### Back
GD will certainly (Batch GD) or almost certainly (Mini-Batch GD)
converge to the <b>global minimum</b> for <b>convex</b> error
surfaces and to a <b>local minimum for non-convex</b> surfaces.
