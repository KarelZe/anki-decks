## Note
nid: 1612170866395
model: Basic-d7a3e
tags: 09_clustering, 09_clustering_2, checklater
markdown: false

### Front
Erklären Sie, wie die <b>link-basierte Methode</b> beim Clustering von <b>kategorischen Daten</b> funktioniert.

### Back
<div>
  <ol>
    <li>
      <div>
        Zwei Punkte werden als Nachbarn betrachtet, wenn
        Ähnlichkeit einen Schwellenwert (\(\theta\)) überschreitet.
        Ähnlichkeitsmaß ist situationsabhängig z. B.
        Jaccard-Koeffizient.
      </div>
    <li>
      <div>
        Dann erzeugt und zählt man die Anzahl der Links zwischen
        zwei Punkten d. h. die gemeinsamen Nachbarn.
      </div>
    <li>
      <div>
        Dann wiederholter Merge von Clustern / Punkten mit max.
        Linkanzahl / die beiden Transaktionen zusammenfassen mit
        größter Anzahl an gemeinsamen Nachbarn. Da es ein
        agglomeratives Verfahren ist, solange bis nur noch ein
        Cluster besteht.
      </div>
  </ol>
</div>
