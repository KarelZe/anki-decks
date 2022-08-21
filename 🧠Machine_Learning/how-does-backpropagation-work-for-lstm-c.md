## Note
nid: 1629293796964
model: Basic-d7a3e
tags: 11_rnns, checklater
markdown: false

### Front
How does backpropagation work for LSTM cells?

### Back
<img src="paste-435c27b7deceeb7bfcdffff568c470a041d52aa1.jpg">
<div>
  Backpropagating from \(c_t\) to \(c_{t-1}\) only elementwise
  multiplication by \(f\), no matrix multiply by \(W\).
</div>
