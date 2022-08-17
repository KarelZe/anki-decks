## Note
nid: 1635929384464
model: Basic-d7a3e
tags: 03_evaluation, repeat
markdown: false

### Front
Explain the <b>nested cross-validation</b>.

### Back
Nested cross validation <b>inner cross validation</b> or <b>outer
cross validation:</b>
<div>
  <ul>
    <li><strong>Inner cross validation:</strong> Splitting data
    into folds and use them multiple times as training and
    validation set. Every inner cross validation selects its own
    (best) parameter combination.
    <li><strong>Outer cross validation:</strong> Repeats inner
    cross validations several times. Before fitting the model by
    inner cross validation, it extracts another fold of the data as
    global holdout set and uses it to test the resulting model.
  </ul>
</div>
<div><img src="vh1sZ.png"></div>
