# Note
```
guid: Bb5w.LIN+|
notetype: Basic-d7a3e-4ce08
```

### Tags
```
checklater
ml::10_neural_networks
```

## Front
How do computational cost of training a neural network grow with no. of layers and no. of units?

## Back
<div>
  <b>Computational cost of forward pass</b>
</div>
<div>
  \(\boldsymbol{z}=\boldsymbol{W} x+\boldsymbol{b}\)
</div>
<div>
  Roughly one add-multiply operation per weight
</div>
<div>
  <b>Computational cost of backward pass</b>
</div>
<div>
  \(\overline{\boldsymbol{W}}=\overline{\boldsymbol{h}}
  \boldsymbol{z}^{T}, \quad
  \overline{\boldsymbol{h}}=\boldsymbol{W}^{T}
  \overline{\boldsymbol{y}}\)
</div>
<div>
  Roughly two add-multiply operations per weight (twice the forward
  pass).
</div>
<div>
  For a MLP this means the the cost is linear with the number of
  layers, quadratic in the number of units per layer.
</div>
