# Note
```
guid: niw;O*)Y*i
notetype: Basic-d7a3e-4ce08
```

### Tags
```
checklater
ml::10_neural_networks
```

## Front
Explain the Backpropagation algorithm.

## Back
Let \(v_1 \cdots v_N\) be a topical ordering of the computation
graph (i. e. parents come before children.) \(V_N\) denotes the
variable we're trying to compute derivates e. g. loss.
<div>
  <img src="paste-e1dd8c4cb6b5298053e89ee19e0448f8fb3389fa.jpg">
  <div>
    <i>Forward pass:</i>
  </div>
  <div>
    For \(i=1, \ldots, N\) Compute \(v_{i}\) as a function of
    \(\operatorname{Pa}\left(v_{i}\right)\)
  </div>
  <div>
    \(\overline{v_{N}}=1\) For \(i=N-1, \ldots, 1\) \(\quad
    \overline{v_{i}}=\sum_{j \in
    \operatorname{Ch}\left(v_{i}\right)} \overline{v_{j}}
    \frac{\partial v_{j}}{\partial v_{i}}\),
  </div>
  <div>
    where \(\operatorname{Ch}\) is the children node and
    \(\operatorname{Pa}\) is the parent node.
  </div>
</div>
