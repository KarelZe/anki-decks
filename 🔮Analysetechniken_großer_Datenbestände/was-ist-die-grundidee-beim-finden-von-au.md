## Note
nid: 1612862293777
model: Basic-d7a3e
tags: 10_id_von_outliern, checklater
markdown: false

### Front
Was ist die Grundidee beim Finden von Ausreisern d. h. ungewöhnlichen Transaktionen in Transaktionsdaten?

### Back
<ol>
  <li>Frequent Pattern Mining als Ausgangspunkt
  <li>Transaktionen, die wenig Frequent Patterns (→ typische
  Muster) enthalten, sind ungewöhnlich. Ein typisches Muster wären
  z. B. Luxusartikel oder Babynahrung.
  <li>Berechnung <em>outlier score</em>:= Summe der Support-Werte
  der Frequent Patterns, die in Transaktion enthalten sind.
</ol>
