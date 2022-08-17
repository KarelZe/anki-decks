## Note
nid: 1611057450839
model: Basic-d7a3e
tags: 09_clustering, 09_clustering_1, checklater
markdown: false

### Front
Wie erfolgt Node-Splitting im <b>CF-Tree</b>?

### Back
<ul>
  <li>Split ist notwendig, wenn Knoten bereits voll ist.
  <li>Die am weitesten voneinander entfernten Punkte sind die Seeds
  (d. h. Ausgangspunkte für das Aufteilen)
  <li>Zuordnung der Punkte (hier Elementarcluster) zum näheren
  Seed.
  <li>Sobald Knoten, der einem Seed entspricht voll ist, wird ein
  anderer Knoten einfach aufgefüllt.
  <li><img src=
  "paste-f3cec80c55f702c290293976bd588b6ed32c44d5.jpg">
  <li>Für Split sind Cluster-Features ausreichend. Man benötigt
  nicht die einzelnen Datenobjekte.
  <li>Ggf. Merge-Schritt (Zusammenfassung von Geschwisterknoten als
  Zwischenschritt sinnvoll).
</ul>
