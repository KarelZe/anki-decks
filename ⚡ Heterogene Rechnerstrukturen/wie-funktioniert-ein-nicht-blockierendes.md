## Note
nid: 1613930923685
model: Basic-d7a3e-4ce08
tags: 06_mpi_openmp
markdown: false

### Front
Wie funktioniert ein <b>nicht-blockierendes Receive</b> bei <b>MPI</b>?

### Back
<div>
<div><ul>
<li><em>MPI_Irecv(&buf, count, datatype, source, tag, comm, &request)</em></li>
<li>Kennzeichnet einen Speicherbereich, der als Empfangspuffer dient.</li>
<li>Die 
Programmbearbeitung wird unmittelbar fortgesetzt ohen darauf zu warten, 
dass die Nachricht in den Anwendungspuffer kopiert worden ist.</li>
<li>Kommunikationstests werden ausgeführt, um den ausstehenden Nachrichtenstatus zu prüfen.</li>
<li>Der Wendungspuffer darf nicht verändert werden, bis <em>MPI_Wait</em> oder <em>MPI_Test</em> anzeigen, dass die nicht-blockierende Receive-Operation ausgeführt worden ist.</li>
</ul>
</div></div>
