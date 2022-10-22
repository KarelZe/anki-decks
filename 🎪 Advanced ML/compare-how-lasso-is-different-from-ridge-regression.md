# Note
```
guid: kGk=7_gRpS
notetype: Basic-d7a3e-4ce08
```

### Tags
```
adv_ml::06_lecture
```

## Front
Compare how <b>LASSO</b> is different from <b>Ridge Regression</b>.

## Back
<b>LASSO</b>
<div>
  <div>
    \[\underset{\beta}{\operatorname{minimize}}
    \sum_{i=1}^{n}\left(y_{i}-\beta_{0}-\sum_{j=1}^{p} \beta_{j}
    x_{i j}\right)^{2} \quad \text { subject to } \quad
    \sum_{j=1}^{p}\left|\beta_{j}\right| \leq s\]
  </div>
  <div><img src=
  "paste-05d4dad6454ba76795c07c8a5ccbd279671d153b.jpg"></div>
  <div>
    <b>Ridge Regression</b>
  </div>
  <div>
    <div>
      \[\underset{\beta}{\operatorname{minimize}}
      \sum_{i=1}^{n}\left(y_{i}-\beta_{0}-\sum_{j=1}^{p} \beta_{j}
      x_{i j}\right)^{2} \quad \text { subject to } \quad
      \sum_{j=1}^{p} \beta_{j}^{2} \leq s\]
    </div>
  </div>
</div>
<div><img src="paste-a2c4b2af878519e9d017137ce07ec7c700b0fba4.jpg"></div>
