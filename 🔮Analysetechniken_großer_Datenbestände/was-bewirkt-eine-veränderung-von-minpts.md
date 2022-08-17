## Note
nid: 1611657050724
model: Basic-d7a3e
tags: 09_clustering, 09_clustering_2, checklater
markdown: false

### Front
Was bewirkt eine Veränderung von <b>minPts</b> und <b>Epsilon</b> bei DBSCAN?

### Back
<ul>
  <li>
    <div>
      Hat Auswirkung auf Dichte und Größe der gefundenen Cluster.
      Wird minPts kleiner, dann sind wir weniger streng, ob Objekt
      zu einem Cluster gehört. Ggf. werden auch Cluster
      zusammengelegt, weil Punkte zwischen zwei Clustern nun auch
      dicht sind.
    </div>
  <li>
    <div>
      Anzahl der gefunden Cluster kann variieren z. B.
      zusammengelegte vs. getrennte Cluster.
    </div>
</ul>
