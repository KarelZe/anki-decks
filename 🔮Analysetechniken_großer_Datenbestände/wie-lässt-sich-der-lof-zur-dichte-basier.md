## Note
nid: 1632904282765
model: Basic-d7a3e
tags: 10_id_von_outliern
markdown: false

### Front
Wie lässt sich der <b>LOF</b> zur Dichte-basierten Outlier-Erkennung interpretieren?

### Back
Ein Wert von etwa \(1\) für \(\operatorname{LOF}(k)\) bedeutet,
dass das Objekt eine mit seinen Nachbarn vergleichbare Dichte hat
(also kein Ausreißer ist).
<div>
  Ein Wert kleiner als \(1\) bedeutet sogar eine dichtere Region
  (was ein sogenannter „Inlier“ wäre), während signifikant höhere
  Werte als \(1\) einen Ausreißer kennzeichnen.
</div>
<div>
  <b>Formel</b>:
</div>
<div>
  \(\operatorname{LOF}_{k}(\mathrm{A}):=\frac{\Sigma_{\mathrm{B}
  \in
  \mathrm{N}_{k}(\mathrm{A})}{\operatorname{lrd}_{k}(\mathrm{B})}{\mid
  \mathrm{rr}_{k}(\mathrm{A})}}{\left|\mathrm{N}_{k}(\mathrm{A})\right|}=\frac{\Sigma_{\mathrm{B}
  \in \mathrm{N}_{k}(\mathrm{A})}
  \operatorname{lrd}_{k}(\mathrm{B})}{\left|\mathrm{N}_{k}(\mathrm{A})\right|
  \cdot \operatorname{lrd}_{k}(\mathrm{A})}\)
</div>
<div>
  <b>Visualisierung</b>:
</div>
<div><img src="sphx_glr_plot_lof_001.png"></div>
