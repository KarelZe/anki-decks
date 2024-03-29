# Note
```
guid: lt2~7]F8uJ
notetype: Basic-d7a3e-4ce08
```

### Tags
```
checklater
ml::03_model_selection
```

## Front
<p>Wie funktioniert die <b>Hold-out-Methode</b> im Kontext von
Trainings- / Testdatensets?

## Back
<div>
  <div>
    Hold-out procedure: \(n\) datapoints available
    \(D=\left\{\left(\boldsymbol{x}_{i},
    y_{i}\right)\right\}_{i=1}^{n}\)
  </div>
  <ol>
    <li>Split into 2
    datasets:\[D_{T}=\left\{\left(\boldsymbol{x}_{i},
    y_{i}\right)\right\}_{i=1}^{m} \quad
    D_{V}=\left\{\left(\boldsymbol{x}_{i},
    y_{i}\right)\right\}_{i=m+1}^{n}\]
    <li>Train on training data to obtain \(\hat{f}_{D{T}}(x)\) for
    each model class \(M\)
    <li>Evaluate resulting estimators on validation data, e.g:
    \(\operatorname{MSE}\left(D_{V},
    \hat{f}_{D{T}}\right)=\frac{1}{n-m}
    \sum_{i=m+1}{n}\left(\hat{f}_{D_{T}}\left(\boldsymbol{x}_{i}\right)-y_{i}\right)^{2}\)
    <li>Pick model with best validation loss
  </ol>
</div>
