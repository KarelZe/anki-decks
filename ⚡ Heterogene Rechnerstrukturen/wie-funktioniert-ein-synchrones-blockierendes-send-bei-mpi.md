# Note
```
guid: p~/OXWeh0l
notetype: Basic-d7a3e-4ce08
```

### Tags
```
06_mpi_openmp
```

## Front
Wie funktioniert ein <b>synchrones, blockierendes Send</b> bei MPI?

## Back
<div>
<div><ul>
<li><em>MPI_Ssend(&buf, count, datatype, dest, tag, comm)</em></li>
<li>Sendet 
eine Nachricht und blockiert, bis der Anwendungspuffer des Senders 
wieder verwendet werden kann und der Empfänger begonnen hat, die 
Nachricht zu empfangen.</li>
</ul>
</div></div>
