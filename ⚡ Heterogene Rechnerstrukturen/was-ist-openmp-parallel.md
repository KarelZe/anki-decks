## Note
nid: 1613912532703
model: Basic-d7a3e-4ce08
tags: 06_mpi_openmp
markdown: false

### Front
Was ist <b>OpenMP parallel</b>?

### Back
<div>
<div><ul>
<li>#pragma omp parallel for [clause[clause]…]</li>
<li>Aufteilen der Schleifeniterationen auf die Threads</li>
<li>Standard: bei m Threads (festglegt mit clause "num_threads(variable)") berechnet jeder Thread N/m Elemente, wobei N z. B. die Zahl der Elemente im Array ist.</li>
<li>Jeder Thread verarbeitet einen Teil der Daten.</li><li><img src="paste-69539ecb91362276f1aac77533bf772bf28aaeab.jpg">
</li>
</ul>
</div></div>
