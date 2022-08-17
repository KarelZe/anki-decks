## Note
nid: 1632904204831
model: Basic-d7a3e
tags: 10_id_von_outliern, checklater, ultra
markdown: false

### Front
Erklären Sie den Dichte-basierten Ansatz <b>LOF</b> zur Ermittlung von Outliern.

### Back
<div>
  <b>Idee</b>:
</div>
<div>
  Unsupervised Ansatz. Dichte eines Punkts mit der Dichte seiner
  Nachbarn zu vergleichen. Punkt, der "dichter" ist als Nachbarn,
  befindet sich im Cluster. Ein Punkt mit geringer Dichte als der
  Nachbar ist ein Ausreißer.
</div>
<div>
  <b>Vorgehen</b>:
</div>
<ul>
  <li>LOF definiert die „lokale Umgebung“ eines Punktes über seine
  \(k\) nächsten Nachbarn. Der Abstand zu diesem wird verwendet, um
  eine lokale Dichte zu schätzen.
  <li>Als Hilfsgröße <i>local reachability distance</i>
  \(\operatorname{lrd}(p)\) wird für die Dichte benötigt. LRD ist
  Kehrwert des Durchschnittsabstands zwischen \(p\) und den Punkten
  in der \(k\)-Nachbarschaft.
  <li>In einem zweiten Schritt wird der Quotient aus den <b>lokalen
  Dichten</b> seiner Nachbarn und der lokalen Dichte des Punktes
  selbst gebildet.
  <li>Hoher \(\operatorname{lof}(p)\) ist Kriterium für ein
  Outlier, weil dann die local reachability density niedriger ist
  als die seiner Nachbarn.
  <li>Quotient ist nahe 1, wenn Punkt in Bereich mit gleichmäßiger
  Dichte fällt.
</ul>
<div>
  <b>Visualisierung:</b>
</div>
<div><img src=
"paste-49d6003857ec38f949db053a4d25904e7e544ff8.jpg"></div>
<div><img src=
"paste-d146c963d15d1a5f694515740290c2d0d34be937.jpg"></div>
<div>
  10 + 8 kommt daher, da man die Distanz nimmt vom Punkt \(P_1\)
  aus, zu seinen zwei nächsten Nachbarn. Die <i>lrd</i> ist der
  Kehrwert des \(k\)-Abstands. Man verwendet Faktor 2 (von \(k=2\))
  im Nenner an, dass es fair wird. Ein LOF von 2.886 spricht für
  einen Ausreißer.
</div>
<div>
  <b>Formeln (nicht in Folien)</b>:
</div>
<div>
  <div>
    \(\operatorname{lrd}_{k}(\mathrm{~A}):=1
    /\left(\frac{\Sigma_{\mathrm{B}} \in
    \mathrm{N}_{k}(\mathrm{~A}) \operatorname {
    reachability-distance }_{k}(\mathrm{~A},
    \mathrm{~B})}{\left|\mathrm{N}_{k}(\mathrm{~A})\right|}\right)\)
  </div>
</div>
<div>
  <b>Intuition:</b> Kehrwert des Durchschnittsabstands zwischen
  \(p\) und den Punkten in der \(k\)-Nachbarschaft.
</div>
<div>
  \(\operatorname{LOF}_{k}(\mathrm{~A}):=\frac{\Sigma_{\mathrm{B}
  \in
  \mathrm{N}_{k}(\mathrm{~A})}{\operatorname{lrd}_{k}(\mathrm{~B})}{\mid
  \mathrm{rr}_{k}(\mathrm{~A})}}{\left|\mathrm{N}_{k}(\mathrm{~A})\right|}=\frac{\Sigma_{\mathrm{B}
  \in \mathrm{N}_{k}(\mathrm{~A})}
  \operatorname{lrd}_{k}(\mathrm{~B})}{\left|\mathrm{N}_{k}(\mathrm{~A})\right|
  \cdot \operatorname{lrd}_{k}(\mathrm{~A})}\)
</div>
<div>
  <b>Intuition:</b> Durchschnitt der Verhältnisse der <i>local
  reachability density</i> von \(p\) und der \(k\) nächsten
  Nachbarn von \(p\).
</div>
