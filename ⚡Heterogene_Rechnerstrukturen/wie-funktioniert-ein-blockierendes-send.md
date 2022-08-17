## Note
nid: 1613929384972
model: Basic-b122e
tags: 06_mpi_openmp
markdown: false

### Front
Wie funktioniert ein <b>blockierendes Send</b> bei <b>MPI</b>?

### Back
<div>
  <div>
    <ul>
      <li><em>MPI_Send(&buf, count, datatype, dest, tag,
      comm)</em>
      <li>Springt nur dann zurück, wenn es sicher ist, dass der
      Anwendungspuffer wiederverwendet werden kann.
      <li>Kann auf verschiedenen Systemen unterschiedlich
      implementiert sein.
      <li>MPI Standard erlaubt die Verwendung eines Systempuffers.
      Fordert es aber nicht.
    </ul>
  </div>
</div>
