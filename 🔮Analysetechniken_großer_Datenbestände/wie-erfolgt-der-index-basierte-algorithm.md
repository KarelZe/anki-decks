## Note
nid: 1632502207107
model: Basic-d7a3e
tags: 10_id_von_outliern, checklater
markdown: false

### Front
Wie erfolgt der <b>Index-basierte Algorithmus</b>?

### Back
k-NN Query für jedes Datenobjekt,<div>Stop, sobald mehr Objekte als erforderlich in der Nachbarschaft sind.</div><div>
</div><div>
</div><div><b>Original-Paper (Knorr):</b></div><div>Basierend auf einer multidimensionalen Indexstruktur wird eine <i>range search</i> mit <b>fixem </b>Radius \(D\) durchgeführt für Objekt \(O\). Sobald mehr als \(M\) (wobei \(M = N (1-p)\)) ist, gefunden wurden in der \(D\) Nachbarschaft, wird die Suche beendet und \(O\) kann kein Outlier mehr sein.</div>
