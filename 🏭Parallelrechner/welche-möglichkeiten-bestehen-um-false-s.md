## Note
nid: 1589399647481
model: Basic-b122e
tags: 2_3_parallelrechner
markdown: false

### Front
Welche Möglichkeiten bestehen um <b>False sharing</b> und <b>Flattern </b>zu minimieren?

### Back
<ul>
  <li>Verkleinern der Seitengröße, da dadurch die
  Wahrscheinlichkeit, dass mehrere unabhängige Datenwörter auf
  einer gemeinsamen Seite liegen, verrringert wird.
  <li>Andererseits verringert eine größere Seite den Aufwand für
  die Seitenverwaltung.
</ul>
