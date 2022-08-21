## Note
nid: 1632988915930
model: Basic-d7a3e
tags: 09_clustering, 09_clustering_2
markdown: false

### Front
Zeigen Sie die Schwäche eines <b>traditionellen Abstandsmaßes</b>
bei <b>kategorischen Variablen</b> auf.

### Back
Man misst Ähnlichkeit mit:
<div>
  similarity \(\left(x_{i}, y_{i}\right):=1\) wenn \(x_{i}=y_{i}\)
  ansonsten 0.
</div>
<div>
  <b>Beispiel</b>:
</div>
<div>
  Input-Daten: \(\{1,2,3,5\},\{2,3,4,5\},\{1,4\},\{6\}\)
  Input-Daten als Punkte:
  \((1,1,1,0,1,0),(0,1,1,1,1,0),(1,0,0,1,0,0)\), \((0,0,0,0,0,1)\)
</div>
<div>
  Abstandsmaß ist Euklidscher Abstand.
</div>
<div>
  Agglomeratives Verfahren.
</div>
<div>
  Zunächst Merge der ersten beiden Punkte; Centroid des neuen
  Clusters ist \((0.5,1,1,0.5,1,0)\). Dann: Merge des dritten und
  des vierten Punkts. Diese Einkäufe haben aber nichts gemeinsam,
  außer das wenige Produkte gekauft wurden und eine große
  Nicht-Überlappung besteht.
</div>
<div>
  <b>Schwäche:</b>
</div>
<div>
  Häufigkeiten bleiben unberücksichtigt. Man misst Unähnlichkeit.
</div>
