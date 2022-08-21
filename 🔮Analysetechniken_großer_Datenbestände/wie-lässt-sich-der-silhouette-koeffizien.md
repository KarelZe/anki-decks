## Note
nid: 1610448174779
model: Basic-d7a3e
tags: 09_clustering, 09_clustering_1, checklater
markdown: false

### Front
<p>Wie lässt sich der Silhouette-Koeffizient interpretieren?
<p>Unterscheiden Sie dabei für <b>einzelne Objekte</b> und eines
<b>Clusterings</b>.

### Back
<p>Silhouette eines Objekts \(o\)
<p>\(s(o) = -1\)<span>: Schlecht,</span> \(o\) <span>ist im Mittel
näher bei den Elementen von B.</span>
<p>\(s(o) = 1\)<span>: Gute Zuordnung von</span> \(o\) <span>zu
seinem Cluster A.</span>
<p><span>Silhouette-Koeffizient</span> \(s_C\) <span>eines
Clusterings: Durchschnitt der Silhouetten aller Objekte</span>
<p>\(0,7 < s_C<=1,0\) <span>– gute Strukturierung</span>
<p>\(0,5 < s_C<= 0,7\) <span>– mittelmäßige
Strukturierung</span>
<p>\(0,25 < s_C<=0,5\) <span>– schwache Strukturierung</span>
<p>\(s_C<=0,25\) <span>– keine Strukturierung</span>
<p><b>Erklärung</b>:
<p><span>Für Werte</span> \(> 0,5\) hat man eine mittelmäßig bis
gute Strukturierung, für Werte zwischen \(0 - 0.5\) keine oder nur
eine geringe Strukturierung und für negative Werte ist das
Clustering wohl falsch.
