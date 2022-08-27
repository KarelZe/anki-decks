## Note
nid: 1629369279303
model: Basic-d7a3e-4ce08
tags: checklater, ml::10_neural_networks, ultra
markdown: false

### Front
What is the intuitition of adding a <b>momentum term</b> to
<b>stochastic gradient descent</b>?

### Back
Moment simulates the inertia (slow adaption) of an object when its
moving, that is, the direction of the previous update is retained
to a certain extent during the update, while the current update
gradient is used to fine-tune the final update direction.
<div>
  By doing so we increase stability and avoid local optimizations.
</div>
<div><img src="SGD.jpg"></div>
