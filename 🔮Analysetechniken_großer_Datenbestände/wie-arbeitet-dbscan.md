## Note
nid: 1611657916858
model: Basic-d7a3e
tags: 09_clustering, 09_clustering_2
markdown: false

### Front
Wie arbeitet <b>DBSCAN</b>?

### Back
<div>
  <b>Pseudocode:</b>
</div>
<div>
  Input <b>P</b> = Punkt, der expandiert wird, <b>C</b> = aktueller
  cluster, \(\epsilon\) und <b>MinPts</b> sind die Parameter des
  Verfahrens.
</div>
<div><img src=
"paste-e9ff7a68e0d4ec01b0a3466f5885e4f954201210.jpg"></div>
<div><img src=
"paste-1990b755f054e314e27061e43b8fe5537a686d41.jpg"></div>
<div>
  <b>Intuition:</b>
</div>
<div>
  Wähle einen Punkte (zufällig) aus dem Datenbestand. Prüfe, ob er
  dicht ist d. h. ob mindestens minPts andere Objekte in
  \(\epsilon\)-Umgebung liegen. Falls ja, dann ist der Punkt ein
  potenzieller Kandidat für ein Cluster und wir fügen alle seine
  Nachbarn dem Cluster hinzu.
</div>
<div>
  Betrachte nun alle seine Nachbarn und prüfe, ob diese ebenfalls
  dicht sind. Falls ja, wiederhole das Spiel von eben (d.h.
  expandiere die Nachbarn um ihre \(\epsilon\)-Umgebung und prüfe
  Dichte der neuen Punkte). Sofern nur dichte-erreichbar (d. h.
  zwar in Epsilon Umgebung, aber selbst nicht dicht), fahre für
  diesen Punkt nicht fort.
</div>
<div>
  Wiederhole dies, bis alle Punkte erreicht wurden. Wähle dann
  einen anderen, noch nicht besuchten Punkt aus. Wiederhole, bis
  alle Punkte besucht wurden.
</div>
