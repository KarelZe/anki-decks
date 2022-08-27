## Note
nid: 1629275233431
model: Basic-d7a3e-4ce08
tags: checklater, ml::11_rnns
markdown: false

### Front
Describe what a <b>convolutional layer</b> is.

### Back
<div>
  Convolutional layers <b>convolve</b> the input and pass its
  result to the next layer.
</div>
<div>
  In a convolutional layer, we apply multiple <b>filters</b> at the
  image to extract different features. Filters always extend the
  full depth of the input volume. Filter has to be learned.
</div>
<div>
  We convolve the filter with the image i. e. we slide over the
  image spartially, computing dot products.
</div>
<div>
  The dot product is given by:
</div>
<div>
  \(w^{T} x+b\)
</div>
<div>
  <b>Visualization:</b>
</div>
<div><img src=
"paste-45943dd0e0e24e5cd3ceac41704eb7d264cb730b.jpg"></div>
<div><img src=
"paste-1f08bdc45f900c733ad728cff19fb90a391f1e5f.jpg"></div>
