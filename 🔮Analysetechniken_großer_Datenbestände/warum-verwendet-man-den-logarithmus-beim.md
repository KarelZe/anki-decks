## Note
nid: 1632638034385
model: Basic-d7a3e
tags: 02_statistik
markdown: false

### Front
Warum verwendet man den Logarithmus beim Bernoulli-Experiment?<div>
</div><div>\(\prod_{i=1}^{n} p^{y_{i}} \cdot(1-p)^{1-y_{i}}\)<div>
</div><div>wobei \(i\) Index des einzelnen Experiments angibt, \(y_i\) den Ausgang des \(i\)-ten Experiments und \(p\) die zugrundeliegende Wahrscheinlichkeit.</div></div>

### Back
<div>
  \(\sum_{i=1}^{n}\left(1-y_{i}\right) \cdot \log (1-p)+y_{i} \cdot
  \log p\)
</div>
<div>
  Man verwendet den Logarithmus (Log-Likelihood-Funktion), da es
  einfacher ist den Logarithmus aufzuaddieren als wiederholt zu
  multiplizieren.
</div>
<div>
  Logarithmus ist monoton, deshalb wird selbes Maximum erreicht.
</div>
