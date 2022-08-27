## Note
nid: 1651241316074
model: Basic-02d89-e0e22
tags: bda::06_trainining_tuning
markdown: false

### Front
Name the steps in the <b>Bayesian search</b>.

### Back
<ol>
  <li>A domain of hyperparameters over which to search
  <li>An objective function which takes in hyperparameters and
  outputs a score that we want to minimize (or maximize)
  <li>The surrogate model of the objective function
  <li><b>A criteria, called a selection function, for evaluating
  which hyperparameters to choose next from the surrogate model</b>
  <li>A history consisting of (score, hyperparameter) pairs used by
  the algorithm to update the surrogate model
</ol>
