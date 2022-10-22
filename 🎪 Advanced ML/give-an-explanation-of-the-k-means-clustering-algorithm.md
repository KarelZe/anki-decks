# Note
```
guid: oq9diO>ybG
notetype: Basic-d7a3e-4ce08
```

### Tags
```
adv_ml::08_clustering
```

## Front
Give an explanation of the \(k\)-means clustering algorithm.

## Back
<ol>
  <li>Randomly assign a number, from \(1\) to \(K\) to each of the
  observations.
  <li>Iterate until the cluster assignments stop changing:
  <ul>
    <li>For each of the \(k\) clusters, compute th ecluster
    centroid. The \(k\)-th cluster centroid is the vector of the
    \(p\) feature means for the observations in the \(k\)-the
    cluster.
    <li>Assign each observation to the cluster whose centeroid is
    closest (where closest is defined using Euclidean distance)
  </ul>
</ol>
<div><img src="paste-77ba72cec8f7f502e3e62fb64180d52190fe871c.jpg"></div>
