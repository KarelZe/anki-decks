## Note
nid: 1606056413802
model: Basic-d7a3e
tags: 02_linear_classification
markdown: false

### Front
<p>Was ist der <b>"0-1-loss"</b> in der <b>linearen
Klassifikation</b> und wie lässt sich dieser <b>optimieren</b>?

### Back
<p><b>Prediction:</b>
<p>
\(y=\operatorname{step}(f(\boldsymbol{x}))=\operatorname{step}\left(\boldsymbol{w}^{T}
\boldsymbol{x}+b\right)\) Predict class 1 for \(f(x)>0\) else
predict class 0 <b>Optimization:</b>
<p>Find \(\boldsymbol{w}\) such that \[
L_{0}(\boldsymbol{w})=\sum_{i}
\mathbb{I}\left(\operatorname{step}\left(\boldsymbol{w}^{T}
\boldsymbol{x}+b\right) \neq y_{i}\right) \] where \(\mathbb{I}\)
returns 1 if the argument is true and \(\sum\) counts the number of
misclassifications
