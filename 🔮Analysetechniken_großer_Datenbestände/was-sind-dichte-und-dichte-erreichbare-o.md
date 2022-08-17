## Note
nid: 1611657525750
model: Basic-d7a3e
tags: 09_clustering, 09_clustering_2, checklater
markdown: false

### Front
Was sind <b>dichte</b> und <b>dichte-erreichbare Objekte</b> bei <b>DBSCAN</b>?

### Back
Objekt ist <b>dicht</b> („core object“ im Folgenden auch) :=
mindestens minPts andere Objekte in Kugel um Objekt mit Radius
\(\epsilon\) (rote Punkte in der Abbildung mit minPts = 3)
<div>
  <b>Dichte-erreichbares Objekt</b> := Objekt in Epsilon-Umgebung
  eines dichten Objekts, das selbst nicht dicht ist. ("Rand des
  Clusters" / gelbes Objekt)
</div>
<div><img src=
"paste-8edc1cb88c08f8a80ca04251d63b0364893c2990.jpg"></div>
