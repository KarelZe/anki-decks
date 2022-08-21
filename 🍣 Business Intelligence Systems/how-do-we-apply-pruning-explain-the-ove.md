## Note
nid: 1635271650541
model: Basic-d7a3e
tags: 06_decision_tree
markdown: false

### Front
How do we apply pruning? Explain the overall process.

### Back
Split data into training and testing set.
<div>
  We build the tree on the training set. For each node pretend to
  <b>remove node + all children</b> from the tree and <b>measure
  performance</b> on <b>testing set</b>.
</div>
<div>
  Greedily remove the one that <b>most improves</b> testing set
  accuracy.
</div>
<div>
  Repeat until further pruning is <b>harmful</b>.
</div>
