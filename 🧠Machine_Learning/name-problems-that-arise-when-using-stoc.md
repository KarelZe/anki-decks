## Note
nid: 1629368643279
model: Basic-d7a3e
tags: 10_neural_networks, checklater
markdown: false

### Front
Name problems that arise when using <b>stochastic gradient
descent</b>?

### Back
<div>
  <div>
    <ul>
      <li><strong>Loss changes quickly in one direction and slowly
      in another</strong> very slow progress along shallow
      dimension, jitter along steep direction
      <li><strong>Loss function has local minima and
      plateaus</strong> gradient descent gets stuck, if gradient is
      zero
      <li><strong>loss function is noisy</strong>, due to
      minibatches
    </ul>
  </div>
</div>
