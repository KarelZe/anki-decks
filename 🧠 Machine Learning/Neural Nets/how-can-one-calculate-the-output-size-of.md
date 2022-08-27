## Note
nid: 1629280090588
model: Basic-d7a3e-4ce08
tags: checklater, ml::11_rnns
markdown: false

### Front
How can one calculate the output size of a convolutional layer
given the parameters
<div>
  <ul>
    <li>Number of filters \(K\)
    <li>Spatial extend kernel size \(F\)
    <li>Stride \(S\)
    <li>Amount of zero padding \(P\)
  </ul>
  <div>
    and the input size \(W_{1} \times H_{1} \times D_{1}\)
  </div>
</div>

### Back
The output size \(W_{2} \times H_{2} \times D_{2}\) is:
<div>
  \(W_{2}=\left(W_{1}-F+2 P\right) / S+1\) \(H_{2}=\left(H_{1}-F+2
  P\right) / S+1\) \(D_{2}=K\)
</div>
<div>
  <b>Example:</b>
</div>
<div>
  Input volume: \(32 \times 32 \times 3\)
</div>
<div>
  10 \(5 \times 5\) filters with stride 1, pad 2.
</div>
<div>
  Output volume size: \((32+2 * 2-5) / 1+1=32\) spatially, so \(32
  \times 32 \times 10\)
</div>
