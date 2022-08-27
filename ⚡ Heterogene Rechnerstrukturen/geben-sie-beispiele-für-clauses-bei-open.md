## Note
nid: 1613931387285
model: Basic-d7a3e-4ce08
tags: 06_mpi_openmp
markdown: false

### Front
Geben Sie Beispiele für <b>Clauses</b> bei <b>OpenMP</b> an.

### Back
<ul>
<li><em>if(skalare Anweisung)</em> → Block wird nur parallelisiert, wenn die Anweisung wahr ist.</li>
<li><em>private (Variablenliste)</em> → Variablen in der Variablenliste werden als privat deklariert. Jeder Thread bekommt seine eigene private Kopie der Variablen.</li>
<li><em>Shared (Variablenliste)</em> → Variablen in der Variablenliste werden als gemeinsam deklariert. Alle Threads haben einen globalen Adressraum.</li></ul>
