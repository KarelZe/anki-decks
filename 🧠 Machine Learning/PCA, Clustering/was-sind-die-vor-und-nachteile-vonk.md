## Note
nid: 1608984955039
model: Basic-d7a3e-4ce08
tags: checklater, ml::05_clustering
markdown: false

### Front
<p>Was sind die <b>Vor- und Nachteile</b> von\(k\)<b>-Means</b>?

### Back
<p style= 
"font-weight:400;letter-spacing:normal;text-indent:0px;text-transform:none;white-space:normal;word-spacing:0px">
<span><strong>Vorteile</strong></span>
<ul style= 
"font-weight:400;letter-spacing:normal;text-indent:0px;text-transform:none;white-space:normal;word-spacing:0px">
  <li><span>K-Means konvergiert typischerweise schnell</span>
  <li><span>K-Means++ garantiert immer noch nicht globale Optima zu
  finden. → mehrmalige Intialisierung mit leicht unterschiedlichen
  Werten für bessere Ergebnisse</span>
</ul>
<p style= 
"font-weight:400;letter-spacing:normal;text-indent:0px;text-transform:none;white-space:normal;word-spacing:0px">
<span><strong>Nachteile</strong></span>
<ul style= 
"font-weight:400;letter-spacing:normal;text-indent:0px;text-transform:none;white-space:normal;word-spacing:0px">
  <li><span>Nur anwendbar wenn (Cluster-) Mittelpunkt definiert ist
  → schwierig bei kategorischen Daten</span>
  <li><span>Kann nicht mit Rauschen und Ausreisern umgehen</span>
  <li><span>Ungeeignet für nicht-konvexe Mengen</span>
</ul>
