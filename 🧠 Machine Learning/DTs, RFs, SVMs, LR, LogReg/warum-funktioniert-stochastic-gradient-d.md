## Note
nid: 1607452836396
model: Basic-d7a3e-4ce08
tags: ml::02_linear_classification
markdown: false

### Front
<p>Warum funktioniert <b>stochastic gradient descent</b> oft besser
als <b>batch gradient descent</b>?

### Back
<div>
  Oftmals enthalten Daten Redundanzen. Berechnung bei <b>batch
  gradient descent</b> sind dann redundant z. B. Gradienten für
  ähnliche Samples oder dieselben Paramtervektoren. Passiert nicht,
  wenn wir unmittelbar nach einer Stichprobe aktualisieren
  (<b>stochastic gradient descent</b>).
</div>
