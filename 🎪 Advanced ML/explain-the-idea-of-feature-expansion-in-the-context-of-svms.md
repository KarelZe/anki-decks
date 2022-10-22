# Note
```
guid: yhTW;zXI+%
notetype: Basic-d7a3e-4ce08
```

### Tags
```
adv_ml::09_lecture
```

## Front
Explain the idea of Feature Expansion in the context of SVMs briefly.

## Back
<div>
  <div>
    <ul>
      <li>Enlarge the space of features by including
      transformations; e.g. \(X_{1}^{2}, X_{1}^{3}, X_{1} X_{2},
      X_{1} X_{2}^{2}, \ldots\) Hence go from a p-dimensional space
      to a \(M>P\) dimensional space.
      <li>Fit a support-vector classifier in the <b>enlarged
      space</b>.
      <li>This results in non-linear decision boundaries in the
      original space.
    </ul>
  </div>
</div>
<div>
  <b>Example</b>
</div>
<div>
  Suppose we use \(\left(X_{1}, X_{2}, X_{1}^{2}, X_{2}^{2}, X_{1}
  X_{2}\right)\) instead of just \(\left(X_{1}, X_{2}\right)\).
  Then the decision boundary would be of the form
  \[\beta_{0}+\beta_{1} X_{1}+\beta_{2} X_{2}+\beta_{3}
  X_{1}^{2}+\beta_{4} X_{2}^{2}+\beta_{5} X_{1} X_{2}=0 \]
</div>
<div>
  This leads to nonlinear decision boundaries in the original space
</div>
