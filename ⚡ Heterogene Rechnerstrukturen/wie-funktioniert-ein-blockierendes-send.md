## Note
nid: 1613929384972
model: Basic-d7a3e-4ce08
tags: 06_mpi_openmp
markdown: false

### Front
Wie funktioniert ein <b>blockierendes Send</b> bei <b>MPI</b>?

### Back
<div>
<div><ul>
<li><em>MPI_Send(&buf, count, datatype, dest, tag, comm)</em></li>
<li>Springt nur dann zurück, wenn es sicher ist, dass der Anwendungspuffer wiederverwendet werden kann.</li>
<li>Kann auf verschiedenen Systemen unterschiedlich implementiert sein.</li>
<li>MPI Standard erlaubt die Verwendung eines Systempuffers. Fordert es aber nicht.</li>
</ul>
</div></div>
