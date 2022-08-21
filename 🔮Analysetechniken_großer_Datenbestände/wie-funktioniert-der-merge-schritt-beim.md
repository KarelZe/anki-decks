## Note
nid: 1611058146216
model: Basic-d7a3e
tags: 09_clustering_1, checklater
markdown: false

### Front
Wie funktioniert der <b>Merge-Schritt</b> beim <b>Einfügen</b> in
den <b>CF-Tree</b>?

### Back
<div>
  Damit nicht Elementarcluster, die eigentlich nahe beieinander
  liegen durch ungünstiges Splitting im Baum weit voneinander
  stehen, können ähnliche Cluster auch gemergt werden.
  <div>
    Man betrachtet die Kinder des Knotens der zwei neue Knoten nach
    Splitting enthält.
  </div>
  <div>
    Man fasst die zwei Kinder mit minimalen Abstand zu einem neuen
    Knoten zusammen (ungleich Split-Ergebnis)
  </div>
  <div>
    GGf. Resplitting der Kinder notwendig.
  </div>
</div>
<div>
  <b>Visualisierung</b>
</div>
<div><img src="41597921.png"></div>
<div>
  (Blatt bereits voll, weil keine 5 CF Platz haben)
</div>
<div><img src="99168547.png"></div>
<div>
  Man will Zwischenergebnis verbessern. Sprich linken Knoten und
  mittleren Knoten zusammenlegen.
</div>
<div>
  Man braucht dann aber nochmal einen Split, weil Kapazität von 4
  überschritten wird.
</div><img src="57805183.png">
<div>
  Hinweis: Punkte entsprechen hier Elementarcluster. Nicht Punkten
  im Datenbestand.
</div>
