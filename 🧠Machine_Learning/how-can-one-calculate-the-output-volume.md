## Note
nid: 1629277015785
model: Basic-d7a3e
tags: 11_rnns, checklater
markdown: false

### Front
How can one calculate the output volume of a pooling layer given its input size \(W_{1} \times H_{1} \times D_{1}\), the kernel size \(F\) and the stride \(S\).

### Back
Output size \(W_{2} \times H_{2} \times D_{2}\) is:
<div>
  \(W_{2}=\left(W_{1}-F\right) / S+1\) \(H_{2}=\left(H_{1}-F\right)
  / S+1\) \(D_{2}=D_{1}\)
  <div><img src="1FHPUtGrVP6fRmVHDn3A7Rw.png"></div>
</div>
