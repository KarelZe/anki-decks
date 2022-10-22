# Note
```
guid: q_X_^P#@d5
notetype: Basic-d7a3e-4ce08
```

### Tags
```
checklater
ml::11_rnns
```

## Front
How does backpropagation work for LSTM cells?

## Back
<img src="paste-435c27b7deceeb7bfcdffff568c470a041d52aa1.jpg">
<div>
  Backpropagating from \(c_t\) to \(c_{t-1}\) only elementwise
  multiplication by \(f\), no matrix multiply by \(W\).
</div>
