## Note
nid: 1610960938783
model: Basic-d7a3e
tags: 09_clustering, 09_clustering_1, checklater
markdown: false

### Front
Wie funktioniert der <b>CLARANS-Algorithmus</b> (Erweiterung von \(k\)-means)?

### Back
<div>CLARANS ist Variante für \(k\)-means. CLARANS löst das Problem von \(k\)-means, dass in jeder Iteration die Medoide verändert werden und alle Datenpunkte gegen die Medoide verglichen werden. CLARANS arbeitet auf einem <b>Sample aus Nachbarn</b> repräsentiert durch die Medoide.</div><div>
</div><div><b>Aufbau</b>:</div><div>
</div><div>Das Finden der \(k\) Medoide ist umgesetzt als Suche in einem Graph. Jeder Knoten im Graph (Menge mit \(k\) Objekten) entspricht einem möglichen Clustering. Menge z. B. \(\left \{p_1, p_2, p_3 \right \}\) gibt an, welche Datenobjekte Medoide von den Clustern sind. Restliche Datenobjekte werden dem Medoid zugeordnet für den Abstand am geringsten ist. <b>Kanten</b> geben an, ob Cluster verbunden sind. Unterscheiden sich zwei Knoten um einen Cluster-Mittelpunkt, dann besteht eine Kante zwischen den Knoten. Graph wird nicht explizit erzeugt und ist nur Vehikel für das Verfahren.</div><div><div>
</div><div><b>Vorgehen:</b></div><div>
</div><div>Einer der Knoten ist Ausgangspunkt für Clustering (<i>Seed</i>). Ausgehend von Knoten wird bestimmte Anzahl an Nachbarn betrachtet. Für Nachbarn kann dann Criterion Function ermittelt werden. Man geht zum Nachbarknoten, sofern sich damit eine niedrigere Criterion Function erzielen lässt.</div><div> </div><div>Man fährt solange fort bis alle Nachbarn einen größeren \(E\)-Wert haben als aktueller Knoten, weil dann lokales Optimum erreicht wurde. Da es sich um ein lokales Optimum handelt, sollte das Clustering mehrmals wiederholt werden.</div></div><div>
</div><div><b>Visualisierung:</b></div><div><img src="50026186.png">
</div>
