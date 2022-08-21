## Note
nid: 1611055685826
model: Basic-d7a3e
tags: 09_clustering, 09_clustering_1, checklater
markdown: false

### Front
Wie erfolgt Einfügen in den CF-Tree bei Radius < \(T\) (d. h. Einfügen in bestehenden Elementar-Cluster)?

### Back
Man ordnet die Punkte in den Baum ein.<div>
</div><div>Man steigt hierfür den Baum hinab und jeder Punkt wandert in den Knoten, zu dessen Centroid er den kleinsten Abstand hat.</div><div>
</div><div>Cluster-Features wird angepasst d. h. N++, aktualisieren der LS und der SS. Berechneter Radius muss dann unterhalb Schwellenwert \(T\) liegen.</div><div>
</div><div><b>Erweiterung:</b></div><div>Wird \(T\) überschritten, so muss ein neuer Elementarcluster erzeugt werden. Wird damit jedoch die maximale Anzahl an Clustern pro Blatt (\(B'\)) überschritten, so muss der Knoten in zwei neue Blattknoten gesplittet werden.</div><div>
</div>
