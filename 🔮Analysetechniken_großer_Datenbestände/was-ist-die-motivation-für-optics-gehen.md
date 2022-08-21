## Note
nid: 1632994936940
model: Basic-d7a3e
tags: 09_clustering, 09_clustering_2, checklater
markdown: false

### Front
Was ist die <b>Motivation </b>für <b>OPTICS</b>? Gehen Sie auf Unterschiede zu <b>DBScan </b>ein.

### Back
<div>
  MinPts bleibt wie bei DBScan. Man möchte aber den schwierig zu
  bestimmenden Parameter \(\varepsilon\) bei DBSCAN ersetzen durch
  einen maximalen Wert \(\underline{\varepsilon}\) den
  \(\varepsilon\) maximal annehmen kann.
</div>
<div>
  Alle möglichen \(\varepsilon\) Werte \(\leq
  \underline{\varepsilon}\) sollen gleichzeitig abgehandelt werden.
</div>
<div>
  Ausgeben möchte man einen sogenannten <b>reachability plot</b>,
  der die Auswirkungen verschiedener \(\varepsilon\) Werte auf das
  Clustering visualisiert. Er plotet an der y-Achse die
  reachability-Distanz, auf der X-Achse sind die Datenobjekte in
  der Reihenfolge geplottet, in der sie von Optics ausgegeben
  werden. Ist einfach vom Anwender zu verstehen. Verschiedene
  Clusterings ergeben sich indem man Horizontale in Diagramm legt.
</div>
<div><img src=
"paste-13903cc0355b7cc71d033ab9dae5d61e27470ca5.jpg"></div>
