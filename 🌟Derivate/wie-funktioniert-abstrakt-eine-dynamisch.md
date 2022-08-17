## Note
nid: 1641818579180
model: Basic-02d89
tags: 05_bewertung, checklater
markdown: false

### Front
Wie funktioniert abstrakt eine <b>dynamische selbstfinanzierende
Strategie</b> zur <b>Duplikation eines Calls</b>?

### Back
<ul><li>Start in \(t=0\). Aufbau einer Position aus \(\Delta\) Basiswerten long. Kreditaufnahme in Höhe der Preisdifferenz, sodass sich als Portfoliowert der Call ergibt.</li><li>In \(t_1\): Anpassung des Bestands an das neue \(\Delta\). Rückzahlung der alten Kreditaufnahme. Neue Kreditaufnahme und glattstellen mit 0.</li><li>Analog für anderen Knoten in \(t_1\)</li><li>Dann Bewertung in \(t=T\) analog zu \(t_1\)</li></ul>
