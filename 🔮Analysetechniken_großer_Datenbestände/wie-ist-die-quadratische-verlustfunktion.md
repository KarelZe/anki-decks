## Note
nid: 1609155712996
model: Basic-d7a3e
tags: 05_evaluation, checklater
markdown: false

### Front
<p>Wie ist die <b>quadratische Verlustfunktion</b> <i>(quadratic
loss function)</i> definiert?

### Back
<div>
  Man kann \(k\) mögliche Vorhersagen machen. Vorhersageverfahren
  liefert Vektor \((p_1, \cdots, p_k)\) mit Summe 1. (z. B.
  Ergebnis des Classifiers: Person ist zu 87 % guter Kunde und zu
  13 % schlechter Kunde).
</div>
<div>
  Tatsächliche Klassenzugehörigkeit als Vektor (onehot-encodierter)
  Vektor \((a_1, \cdots, a_k)\) darstellbar, wobei \(a_i\) den Wert
  1 hat und ansonsten 0.
</div>
<p>\[\mathcal{L}(p,a)=\sum_{j}\left(p_{j}-a_{j}\right)^{2}\]
<p><b>Vorteil</b>:
<p>QL ist symmetrisch. Ein Fehler oberhalb des Targets wirkt sich
auf den Verlust zum gleichen Grad aus wie einer unterhalb des
Targets.
