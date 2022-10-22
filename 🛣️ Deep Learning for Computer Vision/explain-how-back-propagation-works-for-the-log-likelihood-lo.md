# Note
```
guid: tTJ*B|T!1[
notetype: Basic-02d89-e0e22
```

### Tags
```
dl_cv::02_basics_nn
```

## Front
Explain how <b>back propagation</b> works for the <b>log likelihood
loss</b>.

## Back
Minimize loss \(\quad L(\boldsymbol{x}, y ;
\boldsymbol{\theta})=-\sum_{j} y_{j} \log p\left(c_{j} \mid
\boldsymbol{x}\right)\) Derivative with respect to output layer
\(o\) \[ \frac{\partial L}{\partial o}=p(c \mid x)-y \] Loss with
respect to previous block, through chain rule: \[ \begin{array}{ll}
\frac{\partial L}{\partial W^{3}}=\frac{\partial L}{\partial o}
\cdot \frac{\partial o}{\partial W^{3}} & \frac{\partial
L}{\partial \boldsymbol{h}^{2}}=\frac{\partial L}{\partial o} \cdot
\frac{\partial o}{\partial \boldsymbol{h}^{2}} \\ \frac{\partial
L}{\partial W^{3}}=(p(c \mid \boldsymbol{x})-y) \cdot
\boldsymbol{h}^{2} & \frac{\partial L}{\partial
\boldsymbol{h}^{2}}=W^{3} \cdot(p(c \mid
\boldsymbol{x})-\boldsymbol{y}) \end{array} \] Back propagate
derivatives to the previous block: \[ \frac{\partial L}{\partial
W^{2}}=\frac{\partial L}{\partial \boldsymbol{h}^{2}} \cdot
\frac{\partial \boldsymbol{h}^{2}}{\partial W^{2}} \quad
\frac{\partial L}{\partial \boldsymbol{h}^{1}}=\frac{\partial
L}{\partial \boldsymbol{h}^{2}} \cdot \frac{\partial
\boldsymbol{h}^{2}}{\partial \boldsymbol{h}^{1}} \]
<b>Visualization:</b> <img src="paste-57b46ea5c9a6663f8b878a311248a65dc108da45.jpg">
