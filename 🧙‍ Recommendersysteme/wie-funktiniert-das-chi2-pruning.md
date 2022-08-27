## Note
nid: 1593355406000
model: Basic-b122e-20a86
tags: 09_decision_trees
markdown: false

### Front
Wie funktiniert das \(\chi^2\)<b>-Pruning</b>, um unrelevante
Attribute herauszufiltern?

### Back
<div>
  <b>\(\chi^2\)-Test</b>
</div>
<div>
  <i>Hypothesen:</i>
</div>
<div>
  Attribut akzeptabel, wenn es einen Signifikanztest besteht:
  <div>
    <div>
      <ul>
        <li>\(H_{0}\): Kein Muster in den Daten existiert
        <li>\(H_{1}\): Ein Muster existiert
      </ul>
    </div>
  </div>
</div>
<div>
  <i>Vorgehen:</i>
</div>
<div>
  Wir verwerfen \(H_{0}\) auf einem Signifikanzniveau \(\alpha\)
  (meist 5 %), wenn \(D>c\) mit \(c\) bestimmt aus \(P(D \leq
  c)=1-\alpha\) mit \(D\) \(\chi^{2}\) -verteilt mit \(v-1\)
  Freiheitsgraden.
</div>
<div>
  Teststatistik \(D\):
</div>
<div>
  \[D=\sum_{i=1}^{v} \frac{\left(p_{i}-p_{\exp ,
  i}\right)^{2}}{p_{\exp , i}}+\frac{\left(n_{i}-n_{\exp ,
  i}\right)^{2}}{n_{\exp , i}}.\]
</div>
<div>
  \(p\) und \(n\) Anzahl von positiven und negativen Beispielen in
  den Testdaten \(p_{i}\) und \(n_{i}\) Anzahl beobachteter
  positiver und negativer Beispiele für \(i\) -te Ausprägung eines
  Attributs mit \(v\) Werten.
</div>
<div>
  Erwartete Anzahl von positiven und negativen Beispielen unter der
  Annahme völliger Irrelevanz des Attributs aus \[ \begin{array}{l}
  p_{e x p, i}=p \cdot \frac{p_{i}+n_{i}}{p+n} \text { und } \\
  n_{\exp , i}=n \cdot \frac{p_{i}+n_{i}}{p+n} \end{array} \]
  berechnet wird.
</div>
<div>
  Nicht signifikante Attribute werden im Entscheidungsbaum nicht
  verwendet ( daher \(\chi^{2}\) -Pruning).
</div>
