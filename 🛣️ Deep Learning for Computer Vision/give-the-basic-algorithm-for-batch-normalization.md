# Note
```
guid: Mj?gX;:uZS
notetype: Basic-02d89-e0e22
```

### Tags
```
dl_cv::03_nn_basics
```

## Front
Give the <b>basic algorithm</b> for <b>batch normalization</b>.

## Back
<ol>
  <li>compute the empirical <b>mean</b> \(\mu_{k}\) and
  <b>variance</b> \(\sigma_{k}^{2}\) of the batch <b>independently
  for each dimension</b> \(k\).
  <li>
  normalize:\[\hat{x}_{k}=\frac{x_{k}-\mu_{k}}{\sqrt{\sigma_{k}^{2}+\varepsilon}}
  \quad \begin{aligned}&\text { ( } \varepsilon \text { is is
  an arbitrarily small constant } \\&\text { added for
  numerical stability) }\end{aligned}\]
  <li>scale and shift through learnable \(\gamma\) and \(\beta\) :
  \[y_{k}=\gamma_{k} \hat{x}_{k}+\beta_{k}\]
</ol>
