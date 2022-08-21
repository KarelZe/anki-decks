## Note
nid: 1606548230517
model: Basic-d7a3e
tags: 03_model_selection, checklater
markdown: false

### Front
<p>Was unterscheidet <b>true risk</b> von <b>empirical risk</b>?
<p>Gehen Sie dabei auch auf Klassifikation und Regression ein.

### Back
<p><b>True risk: </b>performance on a random test point \((x,y)\)
</p><div>
<div><ul>
<li>Classification: probability of misclassification \(p(y \neq f(x))\)</li>
<li>Regression: expected squared error \(\mathbb{E}_{\boldsymbol{x}, y}\left[(f(\boldsymbol{x})-y)^{2}\right]\)</li><li><b>True risk is unknown!</b></li>
</ul>
</div></div><p><b>Empirical risk:</b> performance on the training set</p><div>
<div><ul>
<li>Classification: proportion of misclassified samples \(\frac{1}{n} \sum_{i} \mathbb{I}\left(f\left(\boldsymbol{x}_{i}\right) \neq y_{i}\right)\)</li>
<li>Regression: average squared error \(\frac{1}{n} \sum_{i}\left(f\left(\boldsymbol{x}_{i}\right)-y_{i}\right)^{2}\)</li><li><b>Empirical risk can be evaluated!</b></li></ul></div></div>
