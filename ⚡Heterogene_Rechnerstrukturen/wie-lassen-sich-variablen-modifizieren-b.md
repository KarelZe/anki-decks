## Note
nid: 1613914879503
model: Basic-b122e
tags: 06_mpi_openmp
markdown: false

### Front
Wie lassen sich <b>Variablen</b> modifizieren bei <b>OpenMP</b>? (4 P)

### Back
<div>
  <div>
    <div>
      <strong>Gemeinsame Variablen</strong>
    </div>
    <ul>
      <li><em>shared(var1, var2, …)</em>
      <li>Ein Wert für alle Threads.
      <li>Kommunikation zwischen Threads möglich.
    </ul>
    <div>
      <strong>Private Variablen</strong>
    </div>
    <ul>
      <li><em>private(var1, var2, …)</em>
      <li>Individueller Wert je Thread.
      <li>Keine Wechselwirkungen mit anderen Threads.
      <li><em>firstprivate(var1, var2, …)</em>
      <li>Wert wird anfangs von gemeinsamen in privaten Bereich
      kopiert.
      <li><em>lastprivate(var1, var2, …)</em>
      <li>Wert aus der letzten Iteration wird am Ende vom privaten
      in den gemeinsamen Bereich kopiert.
    </ul>
  </div>
</div>
