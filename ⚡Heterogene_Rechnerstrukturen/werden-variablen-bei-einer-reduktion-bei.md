## Note
nid: 1613914169273
model: Basic-b122e
tags: 06_mpi_openmp
markdown: false

### Front
Werden <b>Variablen</b> bei einer <b>Reduktion</b> bei OpenMP
verändert?

### Back
Nein, Variablen werden zu <i>firstprivate</i> d. h. anfangs von einem gemeinsamen in einen privaten Bereich kopiert.
