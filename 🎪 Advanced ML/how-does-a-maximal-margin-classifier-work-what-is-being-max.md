# Note
```
guid: ByqM&Y[%fq
notetype: Basic-d7a3e-4ce08
```

### Tags
```
adv_ml::09_lecture
```

## Front
How does a Maximal Margin Classifier work? What is being maximized?

## Back
Among all separating hyperplanes, find the ones that make the
biggest gap or margin between two classes.
<div>
  Constrained optimization problem:
</div>
<div>
  \[\begin{array}{r} \text { maximize } M \text { subject to }
  \sum_{j=1}^{p} \beta_{j}^{2}=1 \\ y_{i}\left(\beta_{0}+\beta_{1}
  x_{i 1}+\ldots+\beta_{p} x_{i p} \geq M \text { for all } i=1,
  \ldots, N\right. \end{array}\]
</div>
