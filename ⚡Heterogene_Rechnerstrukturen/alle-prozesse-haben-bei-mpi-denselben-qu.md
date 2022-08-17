## Note
nid: 1613919347163
model: Basic-b122e
tags: 06_mpi_openmp
markdown: false

### Front
Alle Prozesse haben bei MPI denselben Quellcode.
<div>
  Wie also kann man bei MPI entscheiden, was welcher Prozess welche
  Codeteile ausführt?
</div>

### Back
Unterscheidung über <i>process rank</i>.<div><i>process rank</i> wird während Prozessinitialisierung durch System zugeteilt.
</div>
