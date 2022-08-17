## Note
nid: 1612167479678
model: Basic-d7a3e
tags: 09_clustering, 09_clustering_2, checklater
markdown: false

### Front
Was sind Probleme, die beim <b>Clustering</b> mit <b>kategorischen Daten</b> auftreten?

### Back
<ul>
  <li>Anzahl von kategorischen Attributen ist tendenziell groß z.
  B. Sortimentgröße → Featurevektoren mit sehr hoher
  Dimensionalität (bei entsprechendem Encoding)
  <li>Bei kategorischen Daten reicht es nicht einfach aus
  Übereinstimmung von Einkäufen zu vergleichen z. B. Kunde 1 kauft
  Kaviar 1, Kunde 2 kauft Kaviar 2. Man würde nicht erkennen, dass
  beide Kaviar kaufen.
  <li>Mengen der Items, die Cluster bestimmen, haben
  unterschiedliche Größen z. B. Windeln vs. Luxusartikel im KDW.
  Schwellwert 1 bei Kleinkindsortiment / größerer bei Luxusartikel
  (es gibt X verschiedene Lachse). Schwellwert ist also schwierig
  zu definieren.
  <li>Abstandsmaße sind zu schlicht z. B. Abstand = 0, wenn Wert
  identisch oder schwer zu definieren. z. B. Taxonomie
  erforderlich. Taxonomie aber problematisch, da sie wissen über
  Datenbestand erfordert.
</ul>
