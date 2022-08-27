## Note
nid: 1613914879503
model: Basic-d7a3e-4ce08
tags: 06_mpi_openmp
markdown: false

### Front
Wie lassen sich <b>Variablen</b> modifizieren bei <b>OpenMP</b>? (4 P)

### Back
<div><div><div><div></div><div></div></div></div>
</div>
<div>
<div><div><strong>Gemeinsame Variablen</strong></div>
<ul>
<li><em>shared(var1, var2, …)</em></li>
<li>Ein Wert für alle Threads.</li>
<li>Kommunikation zwischen Threads möglich.</li>
</ul>
<div><strong>Private Variablen</strong></div>
<ul>
<li><em>private(var1, var2, …)</em></li>
<li>Individueller Wert je Thread.</li>
<li>Keine Wechselwirkungen mit anderen Threads.</li>
<li><em>firstprivate(var1, var2, …)</em></li>
<li>Wert wird anfangs von gemeinsamen in privaten Bereich kopiert.</li>
<li><em>lastprivate(var1, var2, …)</em></li>
<li>Wert aus der letzten Iteration wird am Ende vom privaten in den gemeinsamen Bereich kopiert.</li>
</ul>
</div></div>
