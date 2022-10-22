# Note
```
guid: B0cjfXcd:w
notetype: Basic-d7a3e-4ce08
```

### Tags
```
checklater
ml::10_neural_networks
```

## Front
Explain 7 steps on how to train a Neural Net in practice.

## Back
Step 1: Check initial loss
<div>
  Turn off weight decay (L2 regularization), sanity check loss at
  initialization e. g. log(C) for softmax with C classes.
</div>
<div>
  Step 2: Overfit a small sample
</div>
<div>
  Try to train to 100 % accuaracy on a small sample of training
  data (~5-10 minibatches)
</div>
<div>
  <div>
    <div>
      <ul>
        <li>Fiddle with architecture, learning rate, weight
        initialization
        <li>Loss not going down? LR too low, bad initialization
        <li>Loss explodes to Inf or NaN? LR too high, bad
        initialization
      </ul>
    </div>
  </div>
</div>
<div>
  Step 3: Find LR that makes loss go down
</div>
<div>
  Use the architecture from the previous step, use all training
  data, turn on small weight decay, find a learning rate that makes
  the loss drop signifcantly within ~100 iterations.
</div>
<div>
  Step 4: Coarse grid, train for ~1-5 epochs
</div>
<div>
  Choose a few values of learning rate and weight decay (\(\ell_2\)
  loss) around what worked from previous step, train a few models
  for ~1-5 epochs.
</div>
<div>
  Step 5: Refine grid, train longer
</div>
<div>
  Pick best models from Step 4, train them longer (~10-20 epochs)
  without learning rate decay.
</div>
<div>
  Step 6: look at loss curves
</div>
<div>
  Step 7: Go back to step 5
</div>
