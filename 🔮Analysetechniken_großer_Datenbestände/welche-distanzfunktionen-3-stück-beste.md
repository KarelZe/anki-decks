## Note
nid: 1610448175340
model: Basic-d7a3e
tags: 09_clustering, 09_clustering_1, checklater
markdown: false

### Front
<p>Welche Distanzfunktionen (3 Stück) bestehen, um die Distanz
zwischen Clustern zu berechnen?

### Back
<div>
  <b>Single Linkage</b>
</div>
<div>
  Minimale Distanz zwischen zwei Punkten zweier Cluster
</div>
<div>
  \(d\left(C_{k}, C_{l}\right)=\min _{\boldsymbol{x}_{i} \in C_{k}}
  \min _{\boldsymbol{x}_{j} \in C_{l}} d\left(\boldsymbol{x}_{i},
  \boldsymbol{x}_{j}\right)\)
</div>
<div><img src=
"paste-1769a1d2b3eb91d2bcaf68d843fe5208b1741ccd.jpg"></div>
<div>
  <b>Complete Linkage</b>
</div>
<div>
  Maximale Distanz zwischen zwei Datenpunkten zweier Cluster
</div>
<div>
  \(d\left(C_{k}, C_{l}\right)=\max _{\boldsymbol{x}_{i} \in C_{k}}
  \max _{\boldsymbol{x}_{j} \in C_{l}} d\left(\boldsymbol{x}_{i},
  \boldsymbol{x}_{j}\right)\)
</div>
<div><img src=
"paste-9e375eedd4394eb696c28905b4dc118751d18a7f.jpg"></div>
<div>
  <b>Average Linkage</b>
</div>
<div>
  Durchschnittliche Distanz zwischen zwei beliebigen Paaren
</div>
<div>
  \(d\left(C_{k},
  C_{l}\right)=\frac{1}{\left|C_{l}\right|\left|C_{k}\right|}
  \sum_{\boldsymbol{x}_{i} \in C_{l}} \sum_{\boldsymbol{x}_{j} \in
  C_{k}} d\left(\boldsymbol{x}_{i}, \boldsymbol{x}_{j}\right)\)
</div>
<div><img src=
"paste-efd5b89295384446131675ddee1c066c481369f3.jpg"></div>
