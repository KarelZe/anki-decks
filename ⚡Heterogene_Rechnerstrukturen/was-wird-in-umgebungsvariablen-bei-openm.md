## Note
nid: 1613916803452
model: Basic-b122e
tags: 06_mpi_openmp
markdown: false

### Front
Was wird in <b>Umgebungsvariablen</b> bei <b>OpenMP</b> definiert?

### Back
<div>
<div><ul>
<li>Setzen Parameter der Laufzeitumgebung von OpenMP
<ul>
<li>Abfrage zu Beginn der Programmausführung</li>
<li>Änderung der Parameter während Programmausführung nur über Laufzeitroutinen möglich.</li>
</ul>
</li>
</ul>
<div><strong>Beispiel</strong></div>
<ul>
<li><em>omp_set_num_threads():</em> legt die Anzahl der Threads in einem Team fest.</li>
</ul>
</div></div>
