## Note
nid: 1632813170496
model: Basic-d7a3e
tags: 07_association_rules
markdown: false

### Front
Wie steht das <b>Bernoulli-Experiment</b> in Verbindung mit dem <b>Sampling </b>bei <b>Apriori</b>?

### Back
<div>
  Sampling ist eine Variante des Bernoulli-Experiments. Elementares
  Ereignis ist, ob Itemset in Transaktion ist oder nicht. Man hält
  Itemset fest und prüft ob Itemset in Transaktionen enthalten ist,
  und vergibt dann 0 und 1 für Nicht-Vorkommen bzw. Vorkommen.
</div>
<div>
  Man kann dann Wahrscheinlichkeit \(p\) für Vorkommen berechnen.
</div>
<div>
  Darauf aufbauend dann Konfidenzintervalle für den Support im
  Gesamtdatenbestand bestimmen.
</div>
