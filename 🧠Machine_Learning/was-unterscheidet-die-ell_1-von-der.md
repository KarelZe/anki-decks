## Note
nid: 1606548235264
model: Basic-d7a3e
tags: 03_model_selection, checklater
markdown: false

### Front
<p>Was unterscheidet die \(\ell_1\) von der \(\ell_2\) Penalty?</p>

### Back
<div>
  \(\ell_1\) <b>penalty (LASSO):</b>
</div>
<div>
  \(\operatorname{penalty}(\boldsymbol{\theta})=\|\boldsymbol{\theta}\|_{1}=\sum_{d}\left|\theta_{d}\right|\)
</div>
<div>
  Sparse solution bedeutet, dass einige Parameter dann 0 sind.
</div>
<ul>
  <li>Führt dünnbesetzte Lösungen ein
  <li>Schwieriger zu optimieren
</ul>
<div><img src=
"paste-270aa5690d9324d79fc0cc4a0355bfa77404bdac.jpg"></div>
<p>\(\ell_2\) <b>penalty (Ridge):</b>
<p>
\(\operatorname{penalty}(\boldsymbol{\theta})=\|\boldsymbol{\theta}\|_{2}=\sum_{d}
\theta_{d}^{2}\)
<ul>
  <li>einfach zu optimieren, weil konvex
  <li>Geschlossene Lösungen vorhanden
  <li>Parameter sind nahe Null, aber niemals Null
</ul>
<p><img src="paste-f7a7e28c275857b6e61b09184aa1c2970a62ea9e.jpg">
