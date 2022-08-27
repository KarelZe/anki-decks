## Note
nid: 1602355073705
model: Basic-b122e-20a86
tags: 5_1_mpi
markdown: false

### Front
Wie funktioniert <b>Initialisieren</b> und <b>Beenden</b> bei MPI?

### Back
<ul>
  <li>Mit MPI_Init(&argc, &argv); wird initialisiert
  <li>Mit MPI_Finalize(); wird MPI beendet. Ist allerletzte
  Routine!
</ul>
