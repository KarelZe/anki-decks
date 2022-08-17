## Note
nid: 1633014528041
model: Basic-d7a3e
tags: 09_clustering, 09_clustering_2, checklater
markdown: false

### Front
Erklären Sie die <b>reachability distance</b> bei <b>OPTICS</b>.

### Back
<div>Man will Objekte möglichst so hintereinander anordnen, dass Objekt in sortierter Liste möglichst bald auf nahes Core Objekt folgt. Objekt \(o\) wurde bereits in Ausgabeliste eingefügt, \(p\) noch nicht.</div><div>
</div><div>Gem. Definition von Dichte-Erreichbarkeit muss \(o\) dicht sein und \(p\) in der Nachbarschaft liegen.</div><div>
</div><div>Die <i>reachability distance</i> von \(o\) zu \(p\) ist gegeben durch:</div><div>
</div>\(\operatorname{reachDist}_{\underline{\varepsilon}, \text { minPts }}(p, o) = \begin{cases}\text { dist }(p, o) & \text { if } \operatorname{dist}(p, o)>\text { coreDist }_{\text {minPts }}(o) \\ \text { coreDist }_{\text {minPts }}(o) & \text { if dist }(p, o)<\text { coreDist }_{\text {minPts }}(o) \\ \text { undefined } & \text { if } \operatorname{dist}(p, o)>\underline{\varepsilon}\end{cases}\)
<div>
</div><div><b>Erläuterung</b>:</div><div>\(p\) ist Punkt und \(o\) ist Punkt. </div><div>
</div><div>Man interessiert sich nur für Objekte die innerhalb der \(\underline{\varepsilon}\)-Umgebung liegen. Gilt \(\operatorname{dist}(o,p)\) ist größer als \(\underline{\varepsilon}\), dann setzt man die Distanz auf undefined. Indem man nicht direkt erreichbare Objekte außer Acht lässt, will man nahe Objekte möglichst zeitnah abarbeiten.</div><div>
</div><div>Ist \(\varepsilon\) kleiner als <b>Core Distanz</b>, ist \(o\) nicht dicht, weil per Definition <b>Core-Distanz</b> kleinstes \(\varepsilon\) ist, sodass Objekt noch dicht ist. Die Anordnung der Punkte interessiert dann nicht, sofern sie im Core liegen. Bei Ausgabe werden Punkte ohnehin hintereinander ausgegeben.</div><div>
</div><div>Allgemein wenn \(p\) weiter weg von \(o\) als Core Distanz, hängt es i. Allg. von \(\varepsilon\) ab, ob \(p\) von \(o\) dichteereichbar. </div><div>
</div><div><img src="paste-d98123ad7638c79c1536e21f628159332ad3f16b.jpg">
</div><div>
</div><div>Reachability distance ist <b>nicht symmetrisch</b>, weil core-Distanz von \(o\) eingeht, nicht aber von \(p\).</div>
