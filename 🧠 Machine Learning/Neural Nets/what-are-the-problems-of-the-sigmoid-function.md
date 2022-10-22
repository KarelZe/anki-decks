# Note
```
guid: n8e8.K|@E1
notetype: Basic-d7a3e-4ce08
```

### Tags
```
checklater
ml::10_neural_networks
ultra
```

## Front
What are the problems of the <b>sigmoid function</b>?

## Back
<div><ul>
<li>saturated nerons “kill” the gradient, as it stays constant at one</li>
<li>sigmoid outputs are not zero-centered (important for initialization)</li>
<li>\(\exp()\) is expensive to compute, esspecially in deep networks</li>
</ul><div>
</div><div>Due to these problems, sigmoid is today only used for output layers but not for hidden layers.</div>
</div>
