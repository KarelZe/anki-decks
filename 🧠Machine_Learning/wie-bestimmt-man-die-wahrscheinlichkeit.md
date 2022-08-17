## Note
nid: 1609155703835
model: Basic-d7a3e
tags: 06_em_for_dim_reduction
markdown: false

### Front
<p>Wie bestimmt man die Wahrscheinlichkeit, dass \(\boldsymbol{x}\)
in eine Region \(R\) fällt?

### Back
<p>We can also compute \(p(x \in R)\) from samples (If we have
sufficiently large dataset).
<p>\(p(\boldsymbol{x} \in R)=\int_{R} p(\boldsymbol{x}) d
\boldsymbol{x} \approx p(\boldsymbol{x}) V\)
<p>\(V\) the volume e. g. fixed with Parzen Window and
\(\boldsymbol{x}\) is sampled from probability density
\(p(\boldsymbol{x})\)
