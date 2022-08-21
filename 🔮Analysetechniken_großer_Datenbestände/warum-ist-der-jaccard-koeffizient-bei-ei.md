## Note
nid: 1612169859160
model: Basic-d7a3e
tags: 09_clustering, 09_clustering_2, checklater
markdown: false

### Front
Warum ist der Jaccard-Koeffizient bei einem nativen, agglomerativen Clustering ungeeignet? Erklären Sie dies anhand eines Beispiels.

### Back
Für den Datenbestand {1,2,3}, {1,4,5}, {2,3,4}, {1,2,5}, {2,3,5},
{1,3,4}, {2,4,5}, {3,4,5}, {1,2,6}, {1,2,7}, {1,6,7}, {2,6,7}
<div>
  Natürliches Clustering sähe wie folgt aus:
</div>
<div>
  {1,2,3}, {1,4,5}, {2,3,4}, {1,2,5}, {2,3,5}, {1,3,4}, {2,4,5},
  {3,4,5}
</div>
<div>
  und
</div>
<div>
  {1,2,6}, {1,2,7}, {1,6,7}, {2,6,7}
</div>
<div>
  <b>Intuition:</b>
</div>
<div>
  D. h. 1 und 2 wären nicht-diskriminierend, weil in allen
  Transaktionen vorkommend (einzeln oder gemeinsam).
</div>
<div>
  3,4,5 bzw. 6,7 wären diskriminierend, weil als
  Unterscheidungsmerkmal tauglich.
</div>
<div>
  Agglomerativer Algorithmus mit Jaccard-Koeffizient würde aber z.
  B. zuerst {1,2,3} und {1,2,6} clustern. Wichtige Unterscheidung
  wäre verloren, denn wir hören auf lokales Muster.
</div>
