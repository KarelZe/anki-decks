## Note
nid: 1655792405698
model: Basic-02d89
tags: 08_rnn
markdown: false

### Front
Explain how training a <b>RNN</b> to predict the <b>next
character</b> works.

### Back
<ul>
  <li>Intialize model parameters. Draw weights randomly from a
  Gaussian, biases set to 0.
  <li>Perform forward pass, compute prediction scores, apply the
  Soft-max (for classification). Use negative log-likelihood at
  every input.
  <li>Backpropagate gradients from every output. Later outputs are
  used to update parameters "multiple" times. Update model
  parameters using Gradient descent, Adagrad, etc.
  <li>At test time seed first input, calculate output scores and
  compute soft-max, pick the char with the highest score and use as
  input for the next time-step.
</ul>
