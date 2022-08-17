## Note
nid: 1632842879584
model: Basic-d7a3e
tags: 08_constrained_ar, checklater
markdown: false

### Front
Wie lassen sich <b>Teilfolgen</b> im Kontext von Apriori finden?

### Back
<div>
  Eine Folge kann dem Kauf von mehreren Items hintereinander
  entsprechen. Die Reihenfolge ist dann entscheidend.
</div>
<div>
  <b>Beispiel:</b>
</div>
<div>
  <1,3> und <1,2,4> sind Teilfolgen von
  <1,2,3,4>. (z. B. Weglassen von Elementen, Kürzen der
  Folge)
</div>
<div>
  <b>Support einer Folge:</b>
</div>
<div>
  Beispiel: <1,2,3>, <1,2,4>, <4,2>; minsup=50%:
  <1, 2> ist frequent, <2, 4> dagegen nicht. Bei Folgen
  spielt Reihenfolge eine Rolle!
</div>
