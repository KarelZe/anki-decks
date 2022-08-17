## Note
nid: 1613930283831
model: Basic-b122e
tags: 06_mpi_openmp
markdown: false

### Front
Wie funktioniert <b>nicht-blockierendes Send</b> bei <b>MPI</b>?

### Back
<div>
  <div>
    <ul>
      <li><em>MPI_Isend(&buf, count, datatype, dest, tag, comm,
      &request)</em>
      <li>Kennzeichnet einen Speicherbereich, der als Sendpuffer
      dient.
      <li>Die Programmabarbeitung wird unmittelbar fortgesetzt ohne
      darauf zu warten, bis die Nachricht aus dem Anwendungspuffer
      kopiert worden ist.
      <li>Kommunikationstests werden ausgeführt, um den
      ausstehenden Nachrichtenstatus zu prüfen.
      <li>Der Wendungspuffer darf nicht verändert werden, bis
      <em>MPI_Wait</em> oder <em>MPI_Test</em> anzeigen, dass die
      nicht-blockierende Send-Operation ausgeführt worden ist.
    </ul>
  </div>
</div>
