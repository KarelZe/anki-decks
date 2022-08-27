## Note
nid: 1608984952411
model: Basic-d7a3e-4ce08
tags: checklater, ml::05_clustering
markdown: false

### Front
<p>Nennen Sie 4 Methoden, um die Distanz <i>(Cluster Linkage)</i>
zwischen Clustern zu beschreiben.
<p>Was ist jeweils die Intuition?

### Back
<p><b>Single Linkage</b>
<p>Minimale Distanz zwischen zwei Punkten zweier Cluster
<p>\(d\left(C_{k}, C_{l}\right)=\min _{\boldsymbol{x}_{i} \in
C_{k}} \min _{\boldsymbol{x}_{j} \in C_{l}}
d\left(\boldsymbol{x}_{i}, \boldsymbol{x}_{j}\right)\)
<p><img src="paste-1769a1d2b3eb91d2bcaf68d843fe5208b1741ccd.jpg">
<p><b>Complete Linkage</b>
<p>Maximale Distanz zwischen zwei Datenpunkten zweier Cluster
<p>\(d\left(C_{k}, C_{l}\right)=\max _{\boldsymbol{x}_{i} \in
C_{k}} \max _{\boldsymbol{x}_{j} \in C_{l}}
d\left(\boldsymbol{x}_{i}, \boldsymbol{x}_{j}\right)\)
<p><img src="paste-9e375eedd4394eb696c28905b4dc118751d18a7f.jpg">
<p><b>Average Linkage</b>
<p>Durchschnittliche Distanz zwischen zwei beliebigen Paaren
<p>\(d\left(C_{k},
C_{l}\right)=\frac{1}{\left|C_{l}\right|\left|C_{k}\right|}
\sum_{\boldsymbol{x}_{i} \in C_{1}} \sum_{\boldsymbol{x}_{j} \in
C_{k}} d\left(\boldsymbol{x}_{i}, \boldsymbol{x}_{j}\right)\)
<p><img src="paste-efd5b89295384446131675ddee1c066c481369f3.jpg">
<p><b>Centroid Linkage</b>
<p>Distanz zwischen zwei Centroiden
<p>\(d\left(C_{k}, C_{l}\right)=d\left(\frac{1}{\left|C_{l}\right|}
\sum_{\boldsymbol{x}_{i} \in C_{l}} \boldsymbol{x}_{i},
\frac{1}{\left|C_{k}\right|} \sum_{\boldsymbol{x}_{j} \in C_{k}}
\boldsymbol{x}_{j}\right)\)
<p><img src="paste-1597c02f411761888d2c9db1a2990c40f01b3a8a.jpg">
