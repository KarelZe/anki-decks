## Note
nid: 1606548239677
model: Basic-d7a3e
tags: 04_trees_rf, checklater
markdown: false

### Front
<p>Wie ist der <b>Euklidische Abstand</b> definiert?
<p>Unterscheiden Sie den Fall, bei dem Features in derselben
Einheit sind und Features, die erst normalisiert werden müssen.

### Back
<p><b>Fall 1:</b> Daten haben dieselbe Einheit:
<p>\[\left.d(\boldsymbol{x},
\boldsymbol{y})=\|\boldsymbol{x}-\boldsymbol{y}\|=\sqrt{\left(\sum_{k=1}^{d}\left(\boldsymbol{x}_{k}-\boldsymbol{y}_{k}\right)^{2}\right.}\right)\]
<p><b>Fall 2:</b> Daten haben unterschiedliche Einheit, müssen also
normalisiert werden indem:
<p>\(\tilde{\boldsymbol{x}}=(\boldsymbol{x}-\boldsymbol{\mu})
\oslash \boldsymbol{\sigma}\)
<p>Mean \(\mu\), standard deviation \(\sigma\), element-wise
divison (similar to Hardamard product).
<p>\(\tilde{\boldsymbol{x}}\) is standardized with zero mean and
unit variance.
