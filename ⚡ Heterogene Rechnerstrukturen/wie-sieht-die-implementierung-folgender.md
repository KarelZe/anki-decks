## Note
nid: 1613740269213
model: Basic-d7a3e-4ce08
tags: 12_Vektorverarbeitung, het_rs::07_vektorprozessoren
markdown: false

### Front
Wie sieht die Implementierung folgender Matrix-Operation
<div>
  \(Y=a * X+Y\) bei einem Einkern-Prozessor / Vektorprozessor aus?
</div>

### Back
<div>
  Sequenzielle Implementierung:
</div>
<div><img src=
"paste-37a272fe10da071aa899a384acc6dbc43b238efb.jpg"></div>
<div>
  Implementierung für Vektor-Prozessor:
</div>
<div><img src=
"paste-48514d8747fbf19f5a34930f2b7dc5f42cd7f7a1.jpg"></div>
<div>
  <i>Beobachtung:</i>
</div>
<div>
  Adressrechnung entfällt bei Vektorprozessor. Vektorprozessor
  nutzt Pipelining.
</div>
