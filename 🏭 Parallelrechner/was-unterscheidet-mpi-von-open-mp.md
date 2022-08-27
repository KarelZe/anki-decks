## Note
nid: 1602352197436
model: Basic-b122e-20a86
tags: 5_2_open_mp
markdown: false

### Front
Was unterscheidet MPI von Open MP?

### Back
<ul>
  <li><strong>OpenMP</strong> dient klassischerweise der
  Programmierung von <strong>shared memory devices</strong>.
  Parallelität tritt auf, wenn jeder parallele Thread Zugriff auf
  die Daten hat.
  <li><strong>MPI</strong> dient der Programmierung von
  <strong>distributed memory devices</strong>. Die Parallelität
  tritt auf, wenn jeder parallele Prozess in einem isolierten
  Speicherraum rechnet.
</ul>
