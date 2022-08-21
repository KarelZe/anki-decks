## Note
nid: 1608984951728
model: Basic-d7a3e
tags: 05_clustering
markdown: false

### Front
<p>Wie unterscheiden sich die beiden Hierarchical Clustering Ansätze <b>Bottom-Up</b> und <b>Top-Down</b>?</p>

### Back
<ul style= 
"font-weight:400;letter-spacing:normal;text-indent:0px;text-transform:none;white-space:normal;word-spacing:0px">
  <li><strong>Bottom-Up</strong> (agglomerative): Beginnend mit
  jedem Item in seinem eigenen Cluster, finde das beste Paar zur
  Vereinigung in einem neuen Cluster. Wiederhole solange alle
  Cluster vereinigt sind.
  <li><strong>Top-Down</strong> (divisive): Beginnend mit allen
  Daten eines Clusters, betrachte alle Möglichkeiten das Cluster in
  zwei aufzuteilen. Wähle die beste Aufteilung und wiederhole auf
  beiden Seiten.
</ul>
