# Note
```
guid: f(MWY#=eIe
notetype: Basic-d7a3e-4ce08
```

### Tags
```
checklater
ml::10_neural_networks
```

## Front
Explain how XOR can be implemented using a Neural Net?

## Back
<div>
  Recall:
</div>
<div>
  \(XOR(a,b) = (a \operatorname{or} b) \operatorname{and}
  \operatorname{not} (a \operatorname{and} b)\)
</div><b>Architecture:</b>
<div>
  <img src="paste-00f20df6a86ed0946abbfe58c92c82872f849780.jpg">
  <div>
    Hard threshold for activation function (binary units).
  </div>
  <div>
    \(h_{1}\) computes \(x_{1}\) OR \(x_{2}\)
  </div>
  <div>
    \(h_{2}\) computes \(x_{1}\) AND \(x_{2}\)
  </div>
  <div>
    y computers \(h_{1}\) AND NOT \(h_{2}\)
  </div>
</div>
<div><img src="paste-319cebfe22365c7b22818945d6b3cf790251a701.jpg"></div>
<div>
  \(h_1 >=0\) Are both inputs 0, only the bias term (-0.5) would
  impact. Thus -0.5 would not be greater than 0. However, if one
  input term is 1, the sum would be 0.5 which is greater than 0.
  The output would be 1.
</div>
