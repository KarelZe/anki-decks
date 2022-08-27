## Note
nid: 1653716362602
model: Basic-02d89-e0e22
tags: bda::02_classification
markdown: false

### Front
Explain the <b>steps</b> of the <b>CART</b> (Classification and
Regression Tree) algorithm.

### Back
<ul>
  <li>Split training set into 2 subsets using a single feature
  \(k\) and a threshold \(t_{k}\)
  <li>Choose pair \(\left(k, t_{k}\right)\) resulting in „purest“
  subsets (weighted by size)
  <li>Cost function to be minimized: \(\mathrm{J}\left(k,
  t_{k}\right)=\frac{m_{\text {loft }}}{m} G_{\text {left
  }}+\frac{m_{\text {right }}}{m} G_{r i g h t}\)
  <li>Split the two subsets according to previous rules
</ul>
