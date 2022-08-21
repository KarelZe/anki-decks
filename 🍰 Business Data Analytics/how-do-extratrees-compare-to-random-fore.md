## Note
nid: 1653716856608
model: Basic-02d89
tags: 02_classification_bda
markdown: false

### Front
How do <b>ExtraTrees</b> compare to <b>Random Forests</b>?

### Back
<ul>
  <li>Unlike random forests Extra Trees fit each decision tree on
  the whole training dataset
  <li>Like random forest, the Extra Trees algorithm will randomly
  sample the features each
  <li>Unlike random forest, which uses a greedy algorithm to select
  an optimal split point, the Extra Trees algorithm selects a split
  point at random.
  <li>Random selection of split points make the trees less
  correlated similar to random forests, but can increase the
  variance.
</ul>
