## Note
nid: 1632993754336
model: Basic-d7a3e
tags: 09_clustering, 09_clustering_2, checklater
markdown: false

### Front
Was passiert, wenn man \(\underline{\varepsilon}\) (maximaler Wert für \(\varepsilon\) bei OPTICS) sehr groß macht bzw. sehr klein? Was passiert, wenn man <b>MinPts </b>variiert?

### Back
Wenn \(\underline{\varepsilon}\) größer ist, hat man mehr
Variationsmöglichkeiten für \(\varepsilon\). Ist \(
\underline{\varepsilon}\) zu klein, werden Cluster kleiner, mit
größerer Dichte. Große Cluster, mit geringer Dichte bleiben außen
vor.
<div>
  Ist \(\underline{\varepsilon}\) derart groß, dass alle Objekte in
  \(\underline{\varepsilon}\)-Umgebung liegen, dann hätte man
  Performance-Probleme, denn man hätte quadratische Laufzeit.
</div>
<div>
  Macht man <b>MinPts</b> kleiner, so hätte man sehr kleinteilige
  Cluster. Objekte mit wenigen Objekten in Nachbarschaft sind
  bereits dicht (und bilden Cluster). Darstellung in reachability
  Plot zersplittert.
</div>
