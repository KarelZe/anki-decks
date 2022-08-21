## Note
nid: 1612173864101
model: Basic-d7a3e
tags: 09_clustering, 09_clustering_2, checklater
markdown: false

### Front
Wie bringt man unterschiedliche <b>Clusterings</b> bei <b>Cluster Ensembles</b> zusammen?

### Back
<div>
  <strong>Hypergraph Partitioning Algorithmus</strong>
</div>
<ul>
  <li>Jedes <b>Objekt</b> z. B. Kunde ist Knoten eines Graphen
  <li>Für jedes Cluster in einem Clustering-Ergebnis wird eine
  Hyperkante angelegt zwischen den Punkten / Knoten desselben
  Clusters. Sind Objekte innerhalb zweier oder mehrer
  Clustering-Verfahren gleich geclustert bestehen viele Hyperkanten
  zwischen Ihnen.
  <li>Man benötigt zur Auswertung einen Hypergraph Clustering
  Algorithmus. Generell will man Hypergraph so zerlegen, dass eine
  Kostenfunktion für die verletzten Hyperkanten zwischen den Knoten
  minimiert wird. Man erhält dann Clustering zurück, dass bei
  vielen Ensemblemitgliedern im selben Cluster ist.
</ul>
<div><img src= 
"https://media.springernature.com/original/springer-static/image/prt%3A978-0-387-09766-4%2F8/MediaObjects/978-0-387-09766-4_8_Part_Fig3-1_HTML.gif"></div>
<div>
  <strong>Meta-Clustering Algorithmus</strong>
</div>
<ul>
  <li>Darstellung des Clusterings als Graph, wobei Knoten
  unterschiedlichen <b>Clustern</b> entsprechen.
  <li>Kante zwischen Clustern / Knoten bei Überlappung der
  Objekt-Mengen z. B. Jaccard-Koeffizient als Gewicht
  (Kantengewicht =1, wenn gleiches Cluster).
  <li>Kante ist gewichtet, man benötigt deshalb zur Auswertung
  einen Graph-Clustering-Algorithmus, der mit gewichteten Kanten
  hantieren kann.
</ul>
