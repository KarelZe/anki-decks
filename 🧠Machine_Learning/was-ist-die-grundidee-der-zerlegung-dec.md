## Note
nid: 1607857351463
model: Basic-d7a3e
tags: 05_dim_reduction, checklater
markdown: false

### Front
<p>Was ist die Grundidee der <b>Zerlegung</b>
<i>(Decomposition)</i> bei PCA?

### Back
<p>Use \(M << D\) basis vectors:
<p>\(\boldsymbol{x}=\underbrace{\sum_{i=1}^{M} z_{i}
\boldsymbol{u}_{i}}_{\tilde{\boldsymbol{x}} \approx
\boldsymbol{x}}+\underbrace{\sum_{j=M+1}^{D} z_{j}
\boldsymbol{u}_{j}}_{\text {skip }},\)
<p>where \(\boldsymbol{u}_{i}\) are basis vectors and \(z_i\) are
scalars.
<p>We then try to find \(M\) basis vectors \(\boldsymbol{u}_{i}\),
so that the <b>mean squared reproduction error</b> is minimal:
<p>\(\underset{\boldsymbol{u}_{1}, \ldots, \boldsymbol{u}_{M}}{\arg
\min } E\left(\boldsymbol{u}_{1}, \ldots,
\boldsymbol{u}_{M}\right)=\underset{\boldsymbol{u}_{1}, \ldots,
\boldsymbol{u}_{M}}{\arg \min }
\sum_{i=1}^{N}\left\|\boldsymbol{x}_{i}-\tilde{\boldsymbol{x}}_{i}\right\|^{2}\)
