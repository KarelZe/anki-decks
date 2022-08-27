## Note
nid: 1629273878961
model: Basic-d7a3e-4ce08
tags: ml::11_rnns
markdown: false

### Front
What is the problem of processing images with a standard network using fully connected layers?

### Back
Say we got a \(32 \times 32\) image with 3 color channels that
would stretch to an \(3072 \times 1\) array.
<div><img src=
"paste-466385bdbf325602a55808365f8f98792a218407.jpg"></div>
<div>
  We would need a huge amount of weights using a fully-connected
  layer.
</div>
