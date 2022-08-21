## Note
nid: 1606548233273
model: Basic-d7a3e
tags: 03_model_selection, checklater
markdown: false

### Front
<p>Wie funktioniert <b>cross validation</b> mittels <b>random
sub-sampling</b>?

### Back
<ol>
<li>Randomly sample a fraction of \(\alpha \times n\), with \((0 \leq \alpha \leq 1)\) data points for validation.</li>
<li>Train on remaining points and validate, repeat \(K\) times</li></ol><p><img src="paste-2f55ffd1e6783f3cea8c652bd54e3e0fb7672e33.jpg">
</p>
