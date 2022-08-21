## Note
nid: 1629200837897
model: Basic-d7a3e
tags: 10_neural_networks, checklater
markdown: false

### Front
How can testing be done with Drop Out in NN. <div>
</div><div>Name and explain two approaches.</div>

### Back
<div>
  <div>
    <div>
      <strong>Ensemble view:</strong>
    </div>
    <ul>
      <li>Average over multiple dropout masks (computationally
      expensive but quite robust)
      <li>Also allows to get uncertainty estimates (not covered)
    </ul>
    <div>
      <strong>Expectation view:</strong>
    </div>
    <ul>
      <li>Compute the expected input to the activation functions
      <li>Multiply each weight by the dropout rate
    </ul>
  </div>
</div>
