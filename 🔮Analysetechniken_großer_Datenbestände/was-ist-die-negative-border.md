## Note
nid: 1609353649715
model: Basic-d7a3e
tags: 07_association_rules
markdown: false

### Front
<p>Was ist die <b>negative border</b>?</p>

### Back
<p>Die <b>negative border</b> ist abhängig vom minimalen
geforderten Support. Unterhalb der negative Border liegen Itemsets,
die frequent sind und selbst aus frequent items bestehen. Oberhalb
liegen Itemsets, die nicht frequent sind.
<p><span>Wenn dieser Schwellenwert kleiner wird, wandert die
negative border nach oben; es gibt also mehr frequent
Itemsets.</span>
<p>Da man auf einer Stichprobe zunächst arbeitet, wird der Support
zunächst etwas kleiner bzw. etwas größer gewählt als eigentlich für
den Gesamtdatenbestand erforderlich. Dadurch ergibt sich eine Art
Schlauch mit maximalen Frequent Itemsets.
<p><img src="121AujAwRTwJx2xUtbMK.png" style="width: 329px;">
