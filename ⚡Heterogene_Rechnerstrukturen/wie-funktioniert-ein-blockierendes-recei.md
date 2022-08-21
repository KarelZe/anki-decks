## Note
nid: 1613929499289
model: Basic-b122e
tags: 06_mpi_openmp
markdown: false

### Front
Wie funktioniert ein blockierendes Receive bei MPI?

### Back
<div>
  <div>
    <ul>
      <li><em>MPI_Recv(&buf, count, datatype, source, tag,
      comm, &status)</em>
      <li>Springt nur dann zurück, wenn die Nachricht angekommen
      ist und die Daten für die weitere Verarbeitung im Programm
      bereit sind.
    </ul>
  </div>
</div>
