## Note
nid: 1592335030233
model: Basic-d7a3e-4ce08
tags: 04_Architectural_Reuse
markdown: false

### Front
Für was wird das <b>dependency inversion principle</b> benutzt?

### Back
<img src="paste-3c96ab9fa9c2ab392872cffb92546b2ca0217161.jpg">
<div><img src=
"paste-ad3263a34c1530209d0c26a45beb317ec10b02ef.jpg"></div>
<div>
  <div><img src=
  "paste-8a6bb78e37146f84f4edf58441197d08a9e9776d.jpg"></div>
  <div>
    <b>Erklärung Internet:</b>
  </div>
  <div>
    Falls diese Anordnung falsch umgesetzt wird, also Module
    höherer Ebenen von Modulen niedrigerer Ebenen abhängen,
    entsteht ein Problem. Änderungen in Modulen niedrigerer Ebenen
    führen unweigerlich zu Änderungen in Modulen höherer Ebenen.
    Dies widerspricht aber einerseits dem eigentlichen Ansatz der
    Hierarchie, andererseits führt es zu zyklischen Abhängigkeiten.
    Dadurch kommt es zu einer erhöhten Koppelung der Module, welche
    Änderungen in Architektur und Design unnötig verkomplizieren.
    Das Dependency-Inversion-Prinzip nutzt Interfaces, um die
    <b>Abhängigkeitsstruktur</b> zwischen verschiedenen Paketen zu
    invertieren.
  </div>
</div>
