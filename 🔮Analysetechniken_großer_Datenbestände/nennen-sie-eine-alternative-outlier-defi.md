## Note
nid: 1632899194863
model: Basic-d7a3e
tags: 10_id_von_outliern, checklater
markdown: false

### Front
Nennen Sie eine <b>alternative Outlier-Definition</b>.

### Back
Top-\(n\) Punkte sind per Definition Outlier.
<div>
  <div>
    Man bestimmt also den Abstand \(D\) zwischen Punkt \(P\) und
    seinem \(k\)-NN \(D_{k}(P)\) und sortiert dann die Punkte
    absteigend anhand von \(D_{k}(P)\). Der Anwender kann dann
    entscheiden, nach welchem Punkt er abschneidet d. h. welche
    Punkte outlying sind.
  </div>
</div>
<div>
  <b>Visualisierung:</b>
</div>
<div><img src=
"paste-0ce7dc6df3060232ad833e183f4c81045b2f8145.jpg"></div>
<div>
  \(k\) sollte \(k > 1\) sein z. B. 5 oder 10 (je nach
  Beschaffenheit des Datenbestands) zwecks Robustheit.
</div>
