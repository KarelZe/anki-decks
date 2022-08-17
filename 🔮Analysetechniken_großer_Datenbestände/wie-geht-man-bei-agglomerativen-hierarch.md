## Note
nid: 1610960003350
model: Basic-d7a3e
tags: 09_clustering, 09_clustering_1, checklater
markdown: false

### Front
<p>Wie geht man bei <b>agglomerativen hierarchischem Clustering</b>
vor?

### Back
<ol style= 
"font-weight:400;letter-spacing:normal;text-indent:0px;text-transform:none;white-space:normal;word-spacing:0px">
  <li>Jedes Objekt ist einelementiges Cluster
  <li>Berechnung aller paarweisen Abstände zwischen den Clustern /
  zwischen Objekten
  <li>Menge des Paares \(\{A, B\}\) mit dem kleinsten Abstand zu
  neuem Cluster \(C = A \cup B\). Entferne \(A\), \(B\) aus der
  Menge der Cluster und füge \(C\) in die Menge der Cluster ein.
  <li>Abbruch, wenn die aktuelle Menge nur noch aus \(C\) besteht.
  <li>Berechnung der Abstände von \(C\) zu allen anderen Clustern
  in der aktuellen Menge der Cluster, um das Paar mit dem kleinsten
  Abstand zu \(C\) zu finden; gehe zu Schritt 3
</ol>
