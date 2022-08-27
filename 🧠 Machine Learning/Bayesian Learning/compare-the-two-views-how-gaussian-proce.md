## Note
nid: 1631169021010
model: Basic-d7a3e-4ce08
tags: ml::09_bayesian_learning
markdown: false

### Front
Compare the two views how Gaussian processes can be derived.

### Back
<div>
  <div>
    <div>
      <strong>Function view</strong>
    </div>
    <ul>
      <li>A GP is a distribution over functions, where very set of
      N function evaluations is a jointly Gaussian distributed
      <li>Predictions can hence be performed by conditioning
    </ul>
    <div>
      <strong>Weight space view</strong>
    </div>
    <ul>
      <li>Consider a GP as a Bayesian Kernel Regression approach
      <li>Underlying feature space is potentially infinite
      dimensional
      <li>Weight vector is integrated out using kernel trick
    </ul>
  </div>
</div>
