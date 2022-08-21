## Note
nid: 1611056263939
model: Basic-d7a3e
tags: 09_clustering, 09_clustering_1, checklater
markdown: false

### Front
Wie erfolgt <b>Einfügen</b> in den <b>CF-Tree</b> bei neuem Radius
> \(T\) (D. h. Aufmachen neuer Cluster)?

### Back
Man ordnet die Punkte in den Baum ein. Man steigt hierfür den Baum
hinab und jeder Punkt wandert in den Knoten, zu dessen Schwerpunkt
er den kleinsten Abstand hat. Cluster-Features wird angepasst d. h.
N++, aktualisieren der LS und der SS. Man stellt fest dass neuer
Radius des Clusters oberhalb dem Schwellwert \(T\) liegt, dann kann
Objekt <b>nicht</b> in diesen Elementarcluster eingefügt werden.
<div>
  Man macht ggf. neuen Blatt-Cluster.
</div>
<div>
  Knoten werden gesplittet, sobald der Cluster zu groß wird d. h.
  zu viele Teil-Cluster (Elementarcluster) enthält. Die am
  weitesten voneinander entfernten Elementarcluster sind die Seeds.
  Beide Elementarcluster kommen in unterschiedliche Knoten. Übrige
  Elementarcluster werden dann in Blatt zu näherem Elementarcluster
  zugeordnet. Sobald ein Knoten voll ist, wird der andere Knoten
  aufgefüllt.
</div>
<div>
  Zieht Reorganisation des Baums nach sich!
</div>
