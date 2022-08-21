## Note
nid: 1611058643633
model: Basic-d7a3e
tags: 09_clustering, 09_clustering_1, checklater
markdown: false

### Front
Wie lässt sich aus dem CF-Tree das Clustering ermitteln?

### Back
<div>
  Man nimmt genau die Mittelpunkte der Knoten als Cluster.
  Schwierig aber Knoten zu bestimmen, die man als Cluster hernimmt
  wenn z. B. 30 Knoten bestehen k aber k = 10 sein soll. Man könnte
  dann Kriterien nehmen um 10 Cluster zu wählen z. B. Datenraum
  vollständig abdecken, Cluster sollen kompakt sein z. B. wenn
  Linear Sum klein ist aber N groß.
</div>
<div>
  Cluster aus Baum abzulesen ist nicht optimal hinsichtlich
  Qualität z. B. weil Cluster zu groß für T siehe Skizze:
</div>
<div><img src=
"paste-c90f2ed8802a4d151ad4dd2b4c8715bd87f9641f.png"></div>
<div>
  Cluster gehören aber eigentlich zusammen und finden sich an
  unterschiedlichen Stellen im Baum wieder. Man hat dann Probleme
  beim Ablesen der Cluster aus dem Baum.
</div>
<div>
  <div>
    Baum nur verwenden, um Seeds zu ermitteln:
  </div>
  <ul>
    <li>Man schaut sich die einzelnen Datenobjekte an, so wie z. B.
    in den interationen von k-means
    <li>Auch mehrere Varianten denkbar z. B. Initialsieriung wie
    bei \(k\)-means
  </ul>
</div>
