# Note
```
guid: mgOJg=A&wV
notetype: Basic-d7a3e-4ce08
```

### Tags
```
checklater
ml::10_neural_networks
```

## Front
How can testing be done with Drop Out in NN.
<div>
  Name and explain two approaches.
</div>

## Back
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
