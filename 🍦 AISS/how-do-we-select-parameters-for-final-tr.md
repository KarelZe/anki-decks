## Note
nid: 1636445578562
model: Basic-d7a3e-4ce08
tags: 04_deployment, repeat
markdown: false

### Front
How do we select <b>parameters</b> for <b>final training</b>?

### Back
<div>
  <strong>Select parameters for final training:</strong>
</div>
<ul>
  <li><strong>Perform final grid search (optional):</strong>
  Perform a cross validation with Grid Search identify the best
  performing parameters out of the sample parameter search space
  from the evaluation steps.
  <li><strong>Identify best performing parameters</strong>: Check,
  whether performance results lays inside the confidence interval
  identified during the model evlaution phase
</ul>
<div>
  <strong>Train model on all data:</strong>
</div>
<ul>
  <li>All ground truth data is used to train the final model
</ul>
<div><img src=
"paste-9ff13e45ac57a14608f98e9517815c3c6b16598b.jpg"></div>
