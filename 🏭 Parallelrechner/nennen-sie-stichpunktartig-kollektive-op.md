## Note
nid: 1602354768635
model: Basic-b122e-20a86
tags: 5_1_mpi
markdown: false

### Front
Nennen Sie stichpunktartig kollektive Operationen, die in MPI integriert sind.

### Back
<ul>
  <li>MPI_Bcast = Buffer an alle Prozesse schicken
  <li>MPI_Gather = Sammle Daten von allen Prozessen
  <li>MPI_Allgather = Daten von allen Prozessen an alle senden
  <li>MPI_Scatter = Verteile Daten auf alle Prozessoren
  <li>MPI_Reduce = Operationen auf verteilten Daten
  <li>MPI_Allreduce = Ergebnis der Operation an alle senden
  <li>MPI_Op_create / MPI_Op_free = Neue Operation für reduce
  hinzufügen / entfernen
</ul>
<div><img src=
"paste-33c52ff927959ac5429ec77bbe72597e210b9053.jpg"></div>
