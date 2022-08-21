## Note
nid: 1609155716495
model: Basic-d7a3e
tags: 05_evaluation
markdown: false

### Front
<p>Wie ist der <b>relative-squared error</b> definiert? Vollziehen Sie die Berechnung an einem Beispiel nach.</p>

### Back
<p>
\(\frac{\left(p_{1}-a_{1}\right)^{2}+\ldots+\left(p_{n}-a_{n}\right)^{2}}{\left(a_{1}-\bar{a}\right)^{2}+\ldots+\left(a_{n}-\bar{a}\right)^{2}},\)
<div>
  wobei \(p_i\) die Vorhersage für \(i\)-tes Objekt im Datenbestand
  ist und \(a_i\) der tatsächliche Wert.
  <div>
    <b>Beispiel 1</b>:
  </div>
</div>
<div>
  \(p_1 = 500\), \(a_1 = 600\) und \(\bar{a}=100\).
</div>
<div>
  Quotient:
</div>
<div>
  \(100^{2} / 500^{2} \implies\) klein
</div>
<div>
  <b>Beispiel 2:</b>
</div>
<div>
  \(p_1 = 500\), \(a_1 = 600\) und \(\bar{a}=550\)
</div>
<div>
  Quotient:
</div>
<div>
  <div>
    \(100^{2} / 50^{2} \implies \) groß
  </div>
</div>
<div>
  Es macht also einen Unterschied wie weit weg, \(p_1\) und \(a_1\)
  sich vom Mittelwert befinden.
</div>
