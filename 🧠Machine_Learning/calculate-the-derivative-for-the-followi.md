## Note
nid: 1629435684141
model: Basic-d7a3e
tags: 10_neural_networks, checklater
markdown: false

### Front
Calculate the derivative for the following computational graph
using the chain rule.
<div><img src=
"paste-976fda0679c3ce7eff570a48ef8bde4ee4e178af.jpg"></div>
<div>
  \(\begin{aligned} f(x, y) &=y+\exp (x y) \\ x(t) &=\cos t
  \\ y(t) &=t^{2} \end{aligned}\)
</div>

### Back
<div>
  Multivariate chain rule:
</div>
<div>
  \(\frac{d}{d t} f(x(t), y(t))=\frac{\partial f}{\partial x}
  \frac{d x}{d t}+\frac{\partial f}{\partial y} \frac{d y}{d t}\)
</div>
<div>
  \(\begin{aligned} \frac{d}{d t} f(x(t), y(t))=& \frac{\partial
  f}{\partial x} \frac{d x}{d t}+\frac{\partial f}{\partial y}
  \frac{d y}{d t} \\=&(y \exp (x y))(-\sin t) \\ &+(1+x
  \exp (x y))(2 t) \end{aligned}\)
</div>
