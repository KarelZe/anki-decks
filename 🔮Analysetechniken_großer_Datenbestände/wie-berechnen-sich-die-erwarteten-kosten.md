## Note
nid: 1632462641117
model: Basic-d7a3e
tags: 05_evaluation, checklater
markdown: false

### Front
Wie berechnen sich die <b>erwarteten Kosten</b> eines <b>Classifiers</b>?

### Back
\(\operatorname{fp} \cdot(1-p)+p \cdot \operatorname{fn}\)
<div>
  <b>Beispiel</b>:
</div>
<div>
  False Positive (Vorhersage ist YES, Klasse ist NO) kostet 10 ,
  Miss (Vorhersage ist NO, Klasse ist YES) kostet \(1 .\) Richtige
  Vorhersagen „kosten" 0 .
</div>
<div>
  Classifier sagt für ein Objekt vorher: NO mit WS \(=0.7\).
  Erwartete Kosten, wenn wir Vorhersage NO aufgreifen: \(0.3 \cdot
  1\), denn \((0.3 \cdot 1+0.7 \cdot 0)\).
</div>
<div>
  Multiplikation mit Summand ergibt selbst wieder Gerade!
</div>
