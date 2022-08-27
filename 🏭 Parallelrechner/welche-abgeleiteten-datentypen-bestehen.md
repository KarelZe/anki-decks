## Note
nid: 1602354853340
model: Basic-b122e-20a86
tags: 5_1_mpi
markdown: false

### Front
Welche abgeleiteten Datentypen bestehen in MPI?

### Back
<ul>
  <li>MPI_Type_contiguous(...) = bildet einen neuen Typ newtype aus
  count * oldtype
  <li>MPI_Type_vector(...) = konstruiert ein MPI-Array mit
  Elementabstand stride
  <li>MPI_Type_struct(...) = konstruiert einen MPI-Verbund
</ul>
