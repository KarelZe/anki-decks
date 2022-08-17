## Note
nid: 1629179174853
model: Basic-d7a3e
tags: 10_neural_networks, checklater, ultra
markdown: false

### Front
What are the problems of the <b>sigmoid function</b>?

### Back
<div>
  <ul>
    <li>saturated nerons “kill” the gradient, as it stays constant
    at one
    <li>sigmoid outputs are not zero-centered (important for
    initialization)
    <li>\(\exp()\) is expensive to compute, esspecially in deep
    networks
  </ul>
  <div>
    Due to these problems, sigmoid is today only used for output
    layers but not for hidden layers.
  </div>
</div>
