## Note
nid: 1609353652186
model: Basic-d7a3e
tags: 07_association_rules
markdown: false

### Front
<p>Was kann man tun, wenn \(m\)-projected Database bei FP Trees immer noch zu groß für den Speicher ist?</p>

### Back
<div>
  Zerlegung der Datenbank in mehrere Datenbanken (\(x\)-projected
  Database).
</div>
<div>
  Jede \(x\)-projected Database dient dann dazu, bestimmte Menge
  von Frequent Itemsets zu bestimmen.
</div>
<p style= 
"font-weight:400;letter-spacing:normal;text-indent:0px;text-transform:none;white-space:normal;word-spacing:0px">
Noch feiner partitionieren:
<ul style="letter-spacing: normal; text-indent: 0px; 
 text-transform: none; white-space: normal; word-spacing: 0px;">
  <li style="">Menge der Transaktionen, die \(p\), aber nicht \(m\)
  beinhalten.
  <li style="font-weight: 400;">Menge der Transaktionen, die \(p\)
  und \(m\) enthalten.
</ul>
