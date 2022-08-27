## Note
nid: 1629649704363
model: Basic-d7a3e-4ce08
tags: checklater, ml::05_dim_reduction
markdown: false

### Front
How should the dimension \(D\) be chosen for the <b>principal
component analysis</b>?

### Back
<div>
  <ul>
    <li>Choose \(D\) based on <b>application performance</b>, i.e.
    choose the smallest \(D\) that makes the application work well
    enough
    <li>Choose \(D\) so that the Eigenbasis captures <b>some
    fraction of the variance</b> (for example \(\eta= 0.9\). The
    eigenvalue \(\lambda_{i}\) describes the marginal variance
    captured by \(\boldsymbol{u}_i\)
  </ul>
  <div>
    \(\begin{aligned} &\text { Choose } D \text { s.t. }
    \sum_{i=1}^{M} \lambda_{i}=\eta \underbrace{\sum_{i=1}^{D}
    \lambda_{i}}_{\text { Total variance of the data }}\\
    \end{aligned}\)
  </div>
</div>
