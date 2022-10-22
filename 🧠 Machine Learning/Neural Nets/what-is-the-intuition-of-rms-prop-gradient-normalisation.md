# Note
```
guid: Po4-$4X7xV
notetype: Basic-d7a3e-4ce08
```

### Tags
```
checklater
ml::10_neural_networks
```

## Front
What is the intuition of <b>RMS-prop / Gradient Normalisation</b>?

## Back
In RMS-Prop the learning rate is an exponential average of the
gradients instead of a cumulative sum of squared gradients.
<div>
  In plateaus we take larger steps, as they do not have much risk.
  In steep areas take smaller steps.
</div>
