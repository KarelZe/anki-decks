## Note
nid: 1632557339214
model: Basic-d7a3e
tags: 05_evaluation, checklater
markdown: false

### Front
Wenden Sie <b>MDL</b> auf Clustering an.

### Back
<div>MDL kann als objektives Kriterium zum Vergleich verschiedener Clusterings verwendet werden. Gutes Clustering sollte ermöglichen den Bestand \(E\) kompakt darzustellen. Man generiert \(k\) Cluster.</div><div>
</div><div>Mögliche Repräsentation:</div><ul><li>Mittelpunkt der Cluster werden encodiert</li><li>für jedes Element von \(E\)<ul><li>Clusterzugehörigkeit bestimmen und kodieren (\(\log_2 k\) Bits)</li><li>Attributwerte abhängig von Cluster-Mittelpunkt codieren z. B. numerische Abweichung zum Clustermittelpunkt</li></ul></li><li>Wenn Clustering natürlich, ist Beschreibung von \(E\) basierend auf den Clustern kompakter, ansonsten nicht. Weil dann nur die Elemente von \(E\) ohne jegliche Cluster übertragen werden müssen.</li></ul>
