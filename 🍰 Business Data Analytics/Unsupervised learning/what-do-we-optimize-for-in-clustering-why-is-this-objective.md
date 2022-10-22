# Note
```
guid: t/q?A?*y*9
notetype: Basic-02d89-e0e22
```

### Tags
```
bda::07_unsupervised_learning
```

## Front
What do we optimize for in clustering? Why is this objective not optimal?

## Back
Find \(k\) centroids so that the sum of squared distances is minimized
\[\min \sum_{l=1}^{k} \sum_{x_{j} \in C_{i}}\left(x_{j}-\mu_{i}\right)^{2}\]

This optimization problem is hard to solve \(\rightarrow\) heuristic approaches needed
