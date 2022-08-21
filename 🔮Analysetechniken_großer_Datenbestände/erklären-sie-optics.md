## Note
nid: 1633012921439
model: Basic-d7a3e
tags: 09_clustering, 09_clustering_2, checklater
markdown: false

### Front
Erklären Sie <b>OPTICS</b>.

### Back
<div>OPTICS erzeugt kein explizites data set clustering, sondern als Output eine Anordnung der Cluster. Objekte dichter Cluster liegen nahe beieinanander. Die Anordnung kann dann wiederum verwendet werden, um grundlegende Informationen zu den Clustern z. B. Cluster Center zu extrahieren.
</div><div>
</div><div>OPTICS erzeugt eine Anordnung aller Objekte in einer Datenbank. Für jedes Objekt der Datenbank vermerkt es zwei Informationen einmal die core-distance und einmal die reachability-distance.</div><div>OPTICS unterhält eine priority queue, um die Anordnung des Outputs zu generieren. Objekte in der Priority Queue sind nach ihrer <b>reachability distance</b> zu ihrem nächsten <b>Core Objekt</b> angeordnet (aufsteigend).
</div><div>OPTICS beginnt mit einem beliebigen Startpunkt \(p\) der Input Datenbank. Es ermittelt dafür die \(\varepsilon\) Nachbarschaft, setzt die reachability distance auf undefined (weil 1. Objekt) und schreibt den Punkt \(p\) in den Output.</div><div>
</div><div>Handelt es sich bei \(p\) um kein Core Objekt (nicht dicht) fährt man einfach mit dem nächsten Objekt der Priority Queue (oder sofern leer mit der Datenbank) fort. Ist \(p\) hingegen ein Core Objekt, dann aktualisiert OPTICS für jedes Objekt \(q\) in der \(\varepsilon\)-Umgebung von \(p\) die reachability-distance von \(p\) und fügt die \(q\)'s ein in die Priority Queue, sofern \(q\) nicht bereits verarbeitet wurde. Man fährt solange fort, bis aller Input verarbeitet wurde und die Priority Queue leer ist.</div><div>
</div><div>Plottet man die Ausgabe als Säulendiagramm, kann man anhand der Höhe der Säulen die Größe der reachability-distance ablesen. Bildet sich ein Tal aus, bedeutet dass Objekte eine geringe reachability distance haben und ein Cluster bilden. 
</div><div>
</div><div>Das veränderliche \(\varepsilon\) kann man sich als horzontale Linie im reachabilityplot vorstellen, für das die Objekte gerade noch dicht sind.</div><div>
</div><div><b>Beispiel</b>:</div><div><img src="paste-fc2185c8a539b998a8b26b58ff1763320f126540.jpg">
</div><div>
</div><div><b style="">Objekt 1:</b></div><div>Große <i>core distance</i>, weil es zu keinem natürlichen Cluster gehört. </div><div><i>Reachability distance</i> undefiniert, da noch keine Bezugsobjekte in Ergebnis.</div><div></div><div><b>Objekt 2:</b></div><div>Große core distance, weil es zu keinem natürlichen Cluster gehört. Säule für Core distance gleich hoch wie bei 1, weil selbe core distance. reachability distance ist core distance.</div><div></div><div><b style="">Objekt 3:</b></div><div>Hat kleinere core distance. Reachability distance ist Abstand zu 1. Damit deutlich größer als core distance. </div><div></div><div><b>Objekt 4:</b></div><div>Cluster von 3 - 15.  Für großes Spektrum an \(\varepsilon\)-Werten.</div>
