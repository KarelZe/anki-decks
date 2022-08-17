## Note
nid: 1651241316074
model: Basic-02d89
tags: 06_trainining_tuning_bda
markdown: false

### Front
Name the steps in the <b>Bayesian search</b>.

### Back
<ol><li>A domain of hyperparameters over which to search</li><li>An objective function which takes in hyperparameters and outputs a score that we want to minimize (or maximize)</li><li>The surrogate model of the objective function</li><li><b>A criteria, called a selection function, for evaluating which hyperparameters to choose next from the surrogate model</b></li><li>A history consisting of (score, hyperparameter) pairs used by the algorithm to update the surrogate model</li></ol>
