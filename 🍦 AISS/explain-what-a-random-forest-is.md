## Note
nid: 1636530215955
model: Basic-d7a3e-4ce08
tags: 03_evaluation, repeat
markdown: false

### Front
Explain what a <b>random forest</b> is.

### Back
A random forest builds several decision trees on <b>bootstrapped
samples</b>, which is taking multiple samples from the single
training data set. Decision trees are for every instance in
samples. Before every splitting, a random sample of \(m\)
predictors is chosen. Only predictors of this random sample can be
selected for this split.
<div>
  Every decision tree in the forest predicts an outcome. The most
  frequent (classification) or the mean (regression) is the final
  prediction.
</div>
