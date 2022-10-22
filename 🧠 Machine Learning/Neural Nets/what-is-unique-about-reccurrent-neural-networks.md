# Note
```
guid: he}$$h#3.
notetype: Basic-d7a3e-4ce08
```

### Tags
```
checklater
ml::11_rnns
```

## Front
What is unique about <b>Reccurrent Neural Networks</b>?

## Back
We can process a sequence of vectors \(x\) by applying a reccurence
formula at every time step:
<div>
  \(\boldsymbol{h}_{t}=f_{\boldsymbol{W}}\left(\boldsymbol{h}_{t-1},
  \boldsymbol{x}_{t}\right)\)
</div>
<div>
  where \(\boldsymbol{h}_t\) is the new hidden state,
  \(\boldsymbol{h}_{t-1}\) is the previous hidden state, \(x_t\) is
  the input and \(f_{\boldsymbol{W}}\) some function with
  parameters \(\boldsymbol{W}\) e. g. \(\tanh\) function.
  \(\boldsymbol{W}\) is the weight matrix.
</div>
<div>
  The state consists of a single "hidden" vector \(h\) for \(f =
  \tanh\):
</div>
<div>
  \(\boldsymbol{h}_{t}=\tanh \left(\boldsymbol{W}_{h h}
  \boldsymbol{h}_{t-1}+\boldsymbol{W}_{x h}
  \boldsymbol{x}_{t}\right)\)
  \(\boldsymbol{y}_{t}=\boldsymbol{W}_{h y} \boldsymbol{h}_{t}\)
</div>
<div>
  One can clearly see that the hidden state for \(t\) is dependent
  on the Weightmatrix for the last internal state and the input of
  the neural network. tanh is used to compute the next internal
  state.
</div>
<div>
  Note that same parameters and function are used.
</div>
<div>
  As we dependend on the previous step, we require a recursive
  calculation. Hence, the name <b>Recurrent Neural Net</b>.
</div>
<div><img src="paste-b5b85fd9853b59c76953a26ca1100700dd7c43c3.jpg"></div>
<div><img src="https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-MWnh07mnETIlqhjJW0c%2F-Mez-oZInzLyLqK64v0B%2F-Mez8cmuRa0y6Wlhj4Jq%2Fcomputational_graph_rnn.JPG?alt=media&token=a14b29dc-ec2d-4067-917a-01c0cb0bd00d"></div>
