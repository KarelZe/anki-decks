# Note
```
guid: xg5]-khj;d
notetype: Basic-d7a3e-4ce08
```

### Tags
```
checklater
ml::03_model_selection
```

## Front
Explain how the <b>Bias</b> is defined and what it is?

## Back
<div>
  <div>
    \[\mathbb{E}_{x,
    y}\left[\left(\hat{f}_{*}(\boldsymbol{x})-f(\boldsymbol{x})\right)^{2}\right],\]
  </div>
  <div>
    where \(\hat{f}_{*}(\boldsymbol{x})\) is
    \(\mathbb{E}_{D_{n}}\left[\hat{f}_{D_{n}}(\boldsymbol{x})\right]\)
    is the average estimate, averaged over all data sets of size
    \(n\)
  </div>
</div>
<div>
  <ul>
    <li>Difference of the true function to the "best" estimate
    <li>The best is, is the best you can do with your model class
    <li>You take the expectation twice. First expectation
    \(\mathbb{E}_{D_{n}}\) over all data sets of size \(n\), and
    then the second expectation \(\mathbb{E}_{x, y}\) is the error
    in comparsion to the real target for some samples.
  </ul>
</div>
