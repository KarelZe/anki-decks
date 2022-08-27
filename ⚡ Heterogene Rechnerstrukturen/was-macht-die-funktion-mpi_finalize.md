## Note
nid: 1613918120429
model: Basic-d7a3e-4ce08
tags: 06_mpi_openmp
markdown: false

### Front
Was macht die Funktion <i>MPI_Finalize()</i>?

### Back
<div>
<div><ul>
<li>Jeder Prozess muss vor Beendigung <em>MPI_Finalize</em> aufrufen.</li>
<li>Beendigung aller Kommunikationen.</li>
<li>Freigabe aller von MPI allokierten Ressourcen.</li>
</ul>
</div></div>
