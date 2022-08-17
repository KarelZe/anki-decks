## Note
nid: 1588775055398
model: Basic-b122e
tags: 2_parallelrechner
markdown: false

### Front
Bei Symmetrischen Multiprozessorsystemen (SMP) können Prozessoren
über lokale Caches verfügen. Was versteht man in diesem
Zusammenhang unter dem <b>Cash-Kohärenz-Problem</b>?
<div>
  Wie ist Cache-Kohärenz definiert?
</div>

### Back
Replikate in den Caches verschiedener Prozessoren in einem SMP
müssen aktualisiert und kohärent gehalten werden.
<div><img src=
"paste-73c16a682eea5f7d19319e4eb1c1883851ff1632.jpg"></div>
<div>
  <b>Definition:</b>
</div>
<div>
  Eine Cache Speicherverwaltung heißt (cache -) kohärent, falls ein
  Lesezugriff immer den Wert des zeitlich letzten Schreibzugriffs
  auf das entsprechende Speicherwort liefert.
</div>
