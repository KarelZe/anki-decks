## Note
nid: 1613217374608
model: Basic-b122e
tags: 04_koheraenz
markdown: false

### Front
Was sind <b>Spin Locks</b>?

### Back
Ein Sperrmechanismus, der ständig versucht Lock durch einen Prozess
zu aquirieren.
<div>
  Ist Sperrvariable, die kritischen Bereich schützt, frei, wird sie
  auf gesperrt gesetzt, ansonsten wird ihr Status erneut geprüft.
</div>
