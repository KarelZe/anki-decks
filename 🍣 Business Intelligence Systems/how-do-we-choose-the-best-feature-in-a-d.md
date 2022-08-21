## Note
nid: 1635271923504
model: Basic-d7a3e
tags: 06_decision_tree
markdown: false

### Front
How do we choose the <b>best feature</b> in a <b>decision tree</b>?

### Back
At each node, we choose the best feature \(f\) which
<b>maximizes</b> the i<b>nformation gain</b>.
<div>
  Thereby we get a mixture of classes at each node that are more
  and more pure as you go down the tree.
</div>
<div>
  If a node has examples all of one class \(c\), we make it a leaf
  and output \(c\). Otherwise, when we e.g. hit the depth limit, we
  output the most popular class at that node.
</div>
