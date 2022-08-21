## Note
nid: 1616231529510
model: Basic-b122e
tags: 10_Cluster_Modularity
markdown: false

### Front
Welches Problem löst <b>Core Groups Clustering</b> von <b>Plain
Greedy</b> und <b>Randomized Greedy</b>?

### Back
<ul>
  <li>Bei <strong>Plain Greedy</strong> werden Singletons mit immer
  größer werdenden Clustern vereinigt, wodurch Cluster nicht
  gleichmäßig wachsen.
  <li>Bei <strong>Randomized Greedy</strong> wachsen Cluster
  ebenfalls ungleichmäßig, wenn auch weniger stark. Wegen
  nicht-deterministischen Verhalten gibt es Knoten, deren Zuordnung
  zu einem Cluster abhängig von früheren Vereinigungen ist.
  <li>Core Groups Clustering löst das Problem.
</ul>
