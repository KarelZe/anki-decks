## Note
nid: 1613912976059
model: Basic-b122e
tags: 06_mpi_openmp
markdown: false

### Front
Was passiert, wenn man einen Compiler benutzt, der <b>kein</b> <b>OpenMP</b> unterstützt?

### Back
OpenMP ist Direktiv-Basierend.
<div>
  Ist Compiler nicht OpenMP-fähig, werden OpenMP-spezifische
  Direktive als Kommentare interpretiert.
</div>
