## Note
nid: 1613931064077
model: Basic-d7a3e-4ce08
tags: 06_mpi_openmp
markdown: false

### Front
Wie sind <b>Direktive </b>bei <b>OpenMP </b>aufgebaut? Was können Sie enthalten?

### Back
<div>
<div><ul>
<li><em>#pragma omp directive [clause[clause]…]</em></li>
<li>Angaben zur Parallelisierung von Blöcken</li>
<li>Unterscheidung zwischen Direktiven für:
<ul>
<li>Parallelisierung (for, parallel, sections, single, task,…)</li>
<li>Synchronisation (barrier, critical, master, atomic,…)</li>
<li>Daten (threadprivate)</li>
</ul>
</li>
</ul>
</div></div>
