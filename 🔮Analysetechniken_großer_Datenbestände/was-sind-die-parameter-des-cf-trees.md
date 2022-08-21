## Note
nid: 1611055532089
model: Basic-d7a3e
tags: 09_clustering, 09_clustering_1, checklater
markdown: false

### Front
<div>
  <div>
    Was sind die <b>Parameter</b> des <b>CF-Trees</b>?
  </div>
</div>

### Back
<div>Höhenbalancierter Baum mit Parametern:</div><ul><li>\(B\)-Fan-Out (für Innere Knoten) → Anzahl der Abzweigungen → Typischerweise Größe einer Speicherseite</li><li>\(B'\)- Kapazität eines Blatts → Kapazität ist abhängig von Speicherseite</li><li>\(T\) -Schwellenwert:<ul><li>Durchmesser (oder Radius) eines Elementar-Clusters (in Blatt) muss kleiner als \(T\) sein.</li><li>Ohne \(T\) würde Füllgrad der Knoten Struktur des Baums "steuern"</li><li>Ohne \(T\) würden alle Objekte in einem Knoten landen. Es gäbe ein Megacluster.</li></ul></li></ul>
