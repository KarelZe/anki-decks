## Note
nid: 1612171987037
model: Basic-d7a3e
tags: 09_clustering, 09_clustering_2, checklater
markdown: false

### Front
Wie lässt sich \(k\)<b>-means</b> mittels <b>link-basierten Methoden</b> erweitern?

### Back
<ul>
  <li>Punkt wird dem Medoid zugeordnet, zudem der Abstand am
  kleinsten ist.
  <li>D. h. als Abstand zu einem Cluster würde man die Zahl der
  gemeinsamen Links heranziehen.
  <li>Etwa:
    <ul>
      <li>Datenobjekte sind Transaktionen
      <li>Seeds sind ebenfalls Transaktionen
      <li>Abstand - groß gdw. wenn wenige gemeinsame Nachbarn gem.
      Jaccard-Koeffizient bestehen. Bestehen viele gemeinsame
      Nachbarn, wandert man in ein gemeinsames Cluster.
    </ul>
</ul>
