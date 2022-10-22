# Note
```
guid: MY-$%J<&n#
notetype: Basic-d7a3e-4ce08
```

### Tags
```
checklater
ml::07_kernel_methods
ultra
```

## Front
Was ist ein <b>Kernel</b>?

## Back
<div>
  <b>Definition:</b>
</div>
<div>
  Gehe von einer Abbildung \(\varphi: \mathbb{R}^{n} \rightarrow
  \mathbb{R}^{m}\) aus, die unsere Inputvektoren in
  \(\mathbb{R}^{n}\) auf einen feature space \(\mathbb{R}^{m}\)
  abbildet. Dann ist das Skalarprodukt von \(\mathbf{x}\) und
  \(\mathbf{y}\) in diesem Raum \(\varphi(\mathbf{x})^{T}
  \varphi(\mathbf{y})\).
</div>
<div>
  Ein Kernel ist nun eine Funktion \(\kappa\), die dem
  Skalarprodukt entspricht z. B. \(\kappa(\mathbf{x},
  \mathbf{y})=\varphi(\mathbf{x})^{T} \varphi(\mathbf{y})\).
</div>
<div>
  Man erhält also ein Skalar und braucht Berechnung nicht in
  hochdimensionalen Raum durchführen.
</div>
<div>
  <b>Intutition:</b>
</div>Ein Kernel wird verwendet, um das <b>Skalarprodukt</b> zweier
Vektoren \(x\) und \(y\) in einem hochdimensionalen Raum
auszuführen.
