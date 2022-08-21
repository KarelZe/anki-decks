## Note
nid: 1629178371931
model: Basic-d7a3e
tags: 10_neural_networks, checklater
markdown: false

### Front
Explain how the number of input units and the number of output units correspond to the size of the weight matrix of a neural net.

### Back
Each layer connects \(N\) input units to \(M\) output units.
<div>
  Each layer has a \(M \times N\) matrix \(W\).
</div>
<div>
  The output is then calculated as a function of input units:
</div>
<div>
  \(\mathbf{y}=\phi(\mathbf{W} \mathbf{x}+\mathbf{b})\)
</div>
