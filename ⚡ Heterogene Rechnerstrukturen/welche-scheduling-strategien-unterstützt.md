## Note
nid: 1613859902863
model: Basic-d7a3e-4ce08
tags: 06_mpi_openmp
markdown: false

### Front
Welche <b>Scheduling-Strategien</b> unterstützt OpenMP?

### Back
<div>
<div><ul>
<li><strong>static</strong>
<ul>
<li>Arbeitspakete werden gleichmäßig an Threads verteilt</li>
<li>vorteilhaft, wenn jede Iteration gleich viel Zeit benötigt</li>
</ul>
</li>
<li><strong>dynamic</strong>
<ul>
<li>Threads holen dynamisch bei Bedarf neues Arbeitspaket</li>
<li>vorteilhaft, wenn Iterationen utnerschiedlich viel Zeit benötigen → Last-Balancierung</li>
</ul>
</li>
</ul>
</div></div>
