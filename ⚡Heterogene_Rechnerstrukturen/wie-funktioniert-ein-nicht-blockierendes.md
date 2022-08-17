## Note
nid: 1613930923685
model: Basic-b122e
tags: 06_mpi_openmp
markdown: false

### Front
Wie funktioniert ein <b>nicht-blockierendes Receive</b> bei <b>MPI</b>?

### Back
<div>
  <div>
    <ul>
      <li><em>MPI_Irecv(&buf, count, datatype, source, tag,
      comm, &request)</em>
      <li>Kennzeichnet einen Speicherbereich, der als
      Empfangspuffer dient.
      <li>Die Programmbearbeitung wird unmittelbar fortgesetzt ohen
      darauf zu warten, dass die Nachricht in den Anwendungspuffer
      kopiert worden ist.
      <li>Kommunikationstests werden ausgeführt, um den
      ausstehenden Nachrichtenstatus zu prüfen.
      <li>Der Wendungspuffer darf nicht verändert werden, bis
      <em>MPI_Wait</em> oder <em>MPI_Test</em> anzeigen, dass die
      nicht-blockierende Receive-Operation ausgeführt worden ist.
    </ul>
  </div>
</div>
