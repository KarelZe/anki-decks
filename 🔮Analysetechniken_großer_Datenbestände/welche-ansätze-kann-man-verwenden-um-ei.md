## Note
nid: 1610448177087
model: Basic-d7a3e
tags: 09_clustering, 09_clustering_1
markdown: false

### Front
<p>Welche Ansätze kann man verwenden, um eine bessere
Parameterschätzung bei \(k\)<b>-means</b> zu erhalten?

### Back
<div>
  <div>
    <ol>
      <li>Stop-Kriterium d. h. wenn Verbesserung nach x Schritten
      nur noch klein ist oder keine Verbesserung erfolgt wird
      abgebrochen → Obacht Gefahr von lokalem Optima!
      <li>Bestimmung Parameter auf Samples → Stichprobengröße ist
      selbst ein Parameter!
      <li>Mehrere Durchläufe mit unterschiedlicher Initialisierung
      → Anzahl der Runs ist selbst Parameter!
    </ol>
  </div>
</div>
