## Note
nid: 1620474894793
model: Basic-b122e
tags: 07_lecture_rf_dc
markdown: false

### Front
How does one choose the best subtree when pruning a decision tree?

### Back
<div>
<div><ul>
<li>The tuning parameter \(\alpha\) controls a trade-off between the subtree’s complexity and its fit to the training data.</li>
<li>We select an optimal value \(\hat{\alpha}\) using cross-validation.</li>
<li>We then return to the full data set and obtain the subtree corresponding to \(\hat{\alpha}\).</li>
</ul>
</div></div>
