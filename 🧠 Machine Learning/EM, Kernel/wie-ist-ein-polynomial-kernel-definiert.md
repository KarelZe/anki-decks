# Note
```
guid: Ki(@[L(1*6
notetype: Basic-d7a3e-4ce08
```

### Tags
```
checklater
ml::07_kernel_methods
```

## Front
Wie ist ein <b>polynomial kernel</b> definiert?

## Back
<div>
  Kernel für Polynome vom Grad \(d\):
</div>\[\kappa(x, y)=\langle x, y\rangle^{d}\]
<div>
  <b>Beispiel:</b>
</div>
<div>
  Für \(x=\left[x_{1}, x_{2}\right]^{T}\), sei
  \(\phi(x)=\left[x_{1}^{2}, \sqrt{2} x_{1} x_{2},
  x_{2}^{2}\right]\).
</div>
<div>
  Der Kernel ist dann definiert mit: \[\begin{aligned}
  \kappa\left(\boldsymbol{x}, \boldsymbol{x}^{\prime}\right)
  &=x_{1}^{2} x_{1}^{\prime 2}+2 x_{1} x_{2} x_{1}^{\prime}
  x_{2}^{\prime}+x_{2}^{2} x_{2}^{\prime 2} \\ &=\left(x_{1}
  x_{1}^{\prime}+x_{2} x_{2}^{\prime}\right)^{2} \\
  &=\left\langle x, x^{\prime}\right\rangle^{2} \end{aligned}
  \]
</div>
<div><img src="paste-0794fed3b91b29540d61d65276d9b20b14458a0b.jpg"></div>
