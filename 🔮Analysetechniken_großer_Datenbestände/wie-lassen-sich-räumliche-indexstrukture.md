## Note
nid: 1632905351808
model: Basic-d7a3e
tags: 10_id_von_outliern, checklater
markdown: false

### Front
Wie lassen sich räumliche Indexstrukturen verwenden, um obere und
untere Schranke für <i>local outlier factors</i> für jeden
Datenbank zu berechnen?

### Back
<div>
  Man kann Abstand <b>approximieren</b> mit räumlicher
  Indexstruktur. Grüne Strecke (kürzeste Strecke zu Punkt) ist
  untere Schranke. Rote Schränke ist obere Schranke für Abstand
  (und damit Dichte). Liegen Punkte nicht all zu weit entfernt,
  dann hat man eine gute Approximation. <b>LOF eines Punkts eines
  Knotens:</b> Um die untere Schranke LOF eines Punkts P zu
  bestimmen:
</div>
<div>
  Obere Schranke der Dichte von P, untere Schranken der Dichten der
  Nachbarpunkte von P in LOF Formel einsetzen.
</div>
<div>
  Um die Nachbarpunkte zu wählen, betrachtet man alle Knoten des
  Baum, die Überlappungen mit \(k\)-NN Sphäre haben. Man hat dann
  für jedes Rechteck eine untere Schranke der Dichten. Die \(k\)
  Nachbarpunkte mit der niedrigsten unteren Schranke werden
  gewählt. Analog für obere Schranke vorgehen.
</div>
<div>
  <b>Visualisierung:</b>
</div>
<div>
  Im Bild unten würde sich Approximation für Punkte im beigen
  Rechteck bestimmen aus der grünen Distanz (minimale Distanz) und
  roten Distanz (maximale Distanz).
</div>
<div><img src=
"paste-88d33adae747b65d5d210e8cb56d2ddb07c6afc7.jpg"></div>
<div>
  <b>LOF für alle Punkte eines Knotens:</b>
</div>
<div>
  Man kann noch weiter abstrahieren indem man für alle Objekte
  eines Rechtecks den Abstand zu Objekten eines anderen Rechtecks
  abschätzt. Man nimmt an, alle Punkte innerhalb eines Knotens
  liegen auf einer Position. Punkte in anderen Knoten liegen so nah
  wie möglich am Punkt. Damit erhält man obere Schranke. Analog für
  untere Schranke vorgehen, dann in LOF Formel einsetzen. Man hat
  weniger Aufwand, weil für alle Objekte eines Knotens z. B. blauen
  Knoten gültig. Erhebliche Beschleunigung.
</div>
<div>
  <b>Visualisierung:</b>
</div>
<div><img src=
"paste-d0f85e1a79025e569525cdfbcd2734ddbc33b437.jpg"></div>
