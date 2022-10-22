# Note
```
guid: iAPhZ_)l(a
notetype: Basic-d7a3e-4ce08
```

### Tags
```
adv_ml::07_lecture_rf_dc
```

## Front
How does one choose the best subtree when pruning a decision tree?

## Back
<div>
  <div>
    <ul>
      <li>The tuning parameter \(\alpha\) controls a trade-off
      between the subtree’s complexity and its fit to the training
      data.
      <li>We select an optimal value \(\hat{\alpha}\) using
      cross-validation.
      <li>We then return to the full data set and obtain the
      subtree corresponding to \(\hat{\alpha}\).
    </ul>
  </div>
</div>
