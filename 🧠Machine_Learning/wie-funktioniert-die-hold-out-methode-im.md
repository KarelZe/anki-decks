## Note
nid: 1606548231921
model: Basic-d7a3e
tags: 03_model_selection, checklater
markdown: false

### Front
<p>Wie funktioniert die <b>Hold-out-Methode</b> im Kontext von
Trainings- / Testdatensets?

### Back
<div><div>Hold-out procedure: \(n\) datapoints available \(D=\left\{\left(\boldsymbol{x}_{i}, y_{i}\right)\right\}_{i=1}^{n}\)</div>
<ol>
<li>Split into 2 datasets:\[D_{T}=\left\{\left(\boldsymbol{x}_{i}, y_{i}\right)\right\}_{i=1}^{m} \quad D_{V}=\left\{\left(\boldsymbol{x}_{i}, y_{i}\right)\right\}_{i=m+1}^{n}\]</li><li>Train on training data to obtain \(\hat{f}_{D{T}}(x)\) for each model class \(M\)</li>
<li>Evaluate resulting estimators on validation data, e.g: \(\operatorname{MSE}\left(D_{V}, \hat{f}_{D{T}}\right)=\frac{1}{n-m} \sum_{i=m+1}{n}\left(\hat{f}_{D_{T}}\left(\boldsymbol{x}_{i}\right)-y_{i}\right)^{2}\)</li>
<li>Pick model with best validation loss</li>
</ol>
</div>
