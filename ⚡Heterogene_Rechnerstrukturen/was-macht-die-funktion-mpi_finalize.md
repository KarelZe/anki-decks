## Note
nid: 1613918120429
model: Basic-b122e
tags: 06_mpi_openmp
markdown: false

### Front
Was macht die Funktion <i>MPI_Finalize()</i>?

### Back
<div>
  <div>
    <ul>
      <li>Jeder Prozess muss vor Beendigung <em>MPI_Finalize</em>
      aufrufen.
      <li>Beendigung aller Kommunikationen.
      <li>Freigabe aller von MPI allokierten Ressourcen.
    </ul>
  </div>
</div>
