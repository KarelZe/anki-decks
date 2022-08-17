## Note
nid: 1633270284190
model: Basic-d7a3e
tags: 06_ar, zusatzfragen
markdown: false

### Front
<div>
  <div>
    Kein Prune-Schritt bei \(k=2\), warum?
  </div>
</div>

### Back
<div>
  Man konstruiert 2-elementige Kandidaten aus einelementigne
  Frequent Itemsets.
</div>
<div>
  Beim Prune-Schritt würde man nun prüfen, ob {1} bzw. {2} frequent
  sind, da aber die 2-elementige Menge bereits aus \(L_1\)
  konstruiert wurde, ist dies bereits klar. Man betrachtet
  allgemein im Prune-Schritt nur die Teilmengen, die nicht für die
  Kandidatenkonstruktion verwendet wurden.
</div>
