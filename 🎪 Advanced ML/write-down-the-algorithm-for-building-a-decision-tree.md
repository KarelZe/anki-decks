# Note
```
guid: BYG|HK[$~Y
notetype: Basic-d7a3e-4ce08
```

### Tags
```
adv_ml::07_lecture_rf_dc
```

## Front
Write down the <b>algorithm</b> for building a <b>decision
tree</b>.

## Back
<div>
  <div>
    <ol>
      <li>Use recursive binary splitting to grow a large tree on
      the training data, stopping only when each terminal node has
      fewer than some minimum number of observations.
      <li>Apply cost complexity pruning to the large tree in order
      to obtain a sequence of best subtrees, as a function of
      \(\alpha\) .
      <li>Use K-fold cross-validation to choose \(\alpha\) . For
      each \(k=1, \ldots, K\) 3.1. Repeat Steps 1 and 2 on the
      \(\frac{K-1}{K}\) th fraction of the training data, excluding
      the \(k\)-th fold. 3.2. Evaluate the mean squared prediction
      error on the data in the left-out \(k\) th fold, as a
      function of \(\alpha\). Average the results, and pick
      \(\alpha\) to minimize the average error.
      <li>Return the subtree from Step 2 that corresponds to the
      chosen value of \(\alpha\).
    </ol>
  </div>
</div>
