## Note
nid: 1635268300216
model: Basic-d7a3e
tags: 06_decision_tree
markdown: false

### Front
When do we <b>stop </b>with <b>hierarchical clustering</b>?

### Back
Approach 1:
<div>
  Pick no. of cluster \(k\) before hand and stop when we have \(k\)
  clusters.
</div>
<div>
  Approach 2:
</div>
<div>
  Stop when the next merge would create a cluster with low
  "cohesion" (i. e. a "bad" cluster)
</div>
<div>
  Cohesion can be defined by:
</div>
<div>
  <ul>
    <li><b>diameter</b> of the merged cluster / max. distance
    between any pair of points in the cluster
    <li><b>radius</b> / max. distance of a point from centroid (or
    clustroid)
  </ul>
</div>
