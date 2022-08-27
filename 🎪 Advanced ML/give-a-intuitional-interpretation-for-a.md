## Note
nid: 1620472206559
model: Basic-d7a3e-4ce08
tags: adv_ml::07_lecture_rf_dc
markdown: false

### Front
Give a intuitional interpretation for a measure of impurity. When is impurity maximized, when is it minimal?

### Back
1. An impurity measure of a node should be at a maximum when the observations are distributed evenly over all classes in that node, i.e. at
\[\left(\frac{1}{J}, \frac{1}{J}, \ldots, \frac{1}{J}\right)\]
2. An impurity measure of a node should be at a minimum when all observations belong to a single class in that node, i.e. at
\[(1,0, \ldots, 0),(0,1,0, \ldots, 0), \ldots,(0,0, \ldots, 1)\]
3. \(\phi\) is a symmetric function of \(p_{1}, \ldots, p_{J}\).
