# Note
```
guid: xj(26k.UFM
notetype: Basic-d7a3e-4ce08
```

### Tags
```
06_mpi_openmp
```

## Front
Wie funktioniert ein blockierendes Receive bei MPI?

## Back
<div>
<div><ul>
<li><em>MPI_Recv(&buf, count, datatype, source, tag, comm, &status)</em></li>
<li>Springt nur dann zurück, wenn die Nachricht angekommen ist und die Daten für die weitere Verarbeitung im Programm bereit sind.</li>
</ul>
</div></div>
