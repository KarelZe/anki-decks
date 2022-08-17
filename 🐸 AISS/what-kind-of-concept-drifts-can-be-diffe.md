## Note
nid: 1636459475135
model: Basic-d7a3e
tags: 05_concept_drift, repeat
markdown: false

### Front
What kind of <b>concept drifts</b> can be differentiated?

### Back
<ul><li>Real concept drift: changes in \(P(y \mid X), P(X)\) might stay constant or not.</li><li>Virtual drift: \(P(X)\) changes without affecting \(P(y \mid X)\) (Decision boundary stays the same. Distribution of data changes)</li></ul><div><b>Visualization:</b></div><div><img src="paste-051d8571015bba732f6636966c9e1e9518d86a6b.jpg">
</div><div>
</div><div>We see that only the real concept drift changes the decision boundary and the previous decision model becomes obsolete. In reality the virtual drift, changing priors or novelties may appear in combination with the real drift, in those cases the decision boundary is also affected.

<b>Example</b>:
<img src="paste-c8b2fe06c07d880ee3825aa2b999d40d5d26cc20.jpg">
</div>
