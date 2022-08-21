## Note
nid: 1629478617285
model: Basic-d7a3e
tags: 00_klausurfragen
markdown: false

### Front
First, explain the intuition behind slack-variables in support vector machine training. Second, for a single data-point \(\left(x_{i}, c_{i}\right)\) the margin condition with slack variable \(\xi_{i}\) is given as
\[
c_{i}\left(\boldsymbol{w}^{T} \boldsymbol{x}_{i}+b\right) \geq 1-\xi_{i}
\]<div>
</div><div>Assuming \(0 \leq \xi_{i} \leq 1\), is \(x_{i}\) classified correctly? Assuming \(\xi_{i}>1\), is \(x_{i}\) classified correctly?
</div>

### Back
<div>
  <div>
    <div>
      <div>
        <ul>
          <li>Allow violation of margin condition
          <li>Act as regularization, avoid over-fitting
          <li>Make constraint optimization problem solvable, even
          if the data is not linearly separable
        </ul>
        <div>
          Second question:
        </div>
        <ul>
          <li>Yes, (but margin is violated)
          <li>No
        </ul>
      </div>
    </div>
  </div>
</div>
