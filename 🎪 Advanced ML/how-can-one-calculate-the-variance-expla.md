## Note
nid: 1621776969661
model: Basic-d7a3e-4ce08
tags: adv_ml::08_clustering
markdown: false

### Front
How can one calculate the <b>variance</b> explained by a <b>principal component</b>?

### Back
<div>The total variance of a data set is defined as:
</div><div>\[\sum_{j=1}^{P} \operatorname{Var}\left(X_{j}\right)=\sum_{j=1}^{P} \frac{1}{n} \sum_{i=1}^{n} x_{i j}^{2}\]
</div><div>
</div><div>where \(P\) is the number of features and \(n\) is the number of observations.
</div><div>
</div><div>The variance explained by the \(m\) principal components is defined as:</div><div>\[\operatorname{Var}\left(P C A_{m}\right)=\frac{1}{n} \sum_{i=1}^{n} p c a_{i m}^{2}\]
</div><div>
</div><div>Therefore, the proportion of variance explained of the \(m\) th principal component is given by the positive quantity between 0 and 1
\[\frac{\sum_{i=1}^{n} p c a_{i m}^{2}}{\sum_{j=1}^{P} \sum_{i=1}^{n} x_{i j}^{2}}\]

</div>
