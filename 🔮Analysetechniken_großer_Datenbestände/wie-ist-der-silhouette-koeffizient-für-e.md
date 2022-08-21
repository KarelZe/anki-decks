## Note
nid: 1610448174497
model: Basic-d7a3e
tags: 09_clustering, 09_clustering_1, checklater
markdown: false

### Front
<p>Wie ist der <b>Silhouette-Koeffizient</b> für ein <b>Objekt</b>
definiert?

### Back
<div><img src="paste-8971ebf77dd524c384578e5370a2698fd2b19751.jpg">
</div><div>
</div><p>\(a(o)\): Durchschnittliche Distanz zwischen Objekt \(o\) und Objekten in seinem Cluster (A im Folgenden):</p><div>
</div><div>\(a(o)=\frac{1}{|C(o)|} \sum_{p \in C(o)} \operatorname{dist}(o, p)\)
</div><div>
</div><div>\(b(o)\) Durchschnittliche Distanz zwischen o und Objekten im zweitnächsten Cluster (B im Folgenden):</div><div>
</div><div>\(b(o)=\min _{C_{i} \neq C(o)}\left(\frac{1}{\left|C_{i}\right|} \sum_{p \in C_{i}} \operatorname{dist}(o, p)\right)\)
</div><div>
</div><div>Silhouette von Objekt \(o\):</div><div>\(s(o)=\left\{\begin{array}{cc}0 & \text { if } a(o)=0 \text {, i.e., }\left|C_{i}\right|=1 \\ \frac{b(o)-a(o)}{\max \{a(o), b(o)\}} & \text { else }\end{array}\right.\)
</div><div>
</div><div>Wertebereich der Silhouette: \([-1,1]\)</div><p><span style="letter-spacing: 0.01071em;"><b>Intuition: </b></span></p><p><span>Silhouette-Koeffizent von 1 ist optimal, wenn a(o) = 0 ist und b(o) nahe 1 → Man teilt dann 1 / 1 = 1. Alle Punkte desselben Clusters liegen nahe am betrachteten Punkt o. Übrige Punkte in anderen Clustern sind davon entfernt.</span></p><p>Ordnet man in Skizze oben jedoch Punkt o dem Cluster (b) zu, dann wäre b(o) das neue a(o) und a(o) das neue b(o). Man sieht aber, dass dann aber die Distanz zwischen b(o) kleiner ist als zum eigenen Cluster a(o).  Man erhält einen negativen Silhouette-Koeffizienten.</p><p>Fallunterscheidung, wenn o einzigstes Element von A ist. Per Konvention dann 0.</p>
