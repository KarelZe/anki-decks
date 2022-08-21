## Note
nid: 1613913511160
model: Basic-b122e
tags: 06_mpi_openmp
markdown: false

### Front
Wie funktioniert das Programmiermodell <b>Shared Memory Model</b>?

### Back
<div>
  <div>
    <ul>
      <li>Alle Threads haben Zugriff am gemeinsamen globalen
      Speicher.
      <li>Daten können gemeinsam (<em>shared</em>) (→ Zugriff für
      alle Threads) oder privat (<em>private</em>) (→ Zugriff nur
      für einen Thread).
      <li>Datentransfer ist transparent für Programmierer.
      <li>Synchronisation meist implizit.
      <li><img src= 
      "paste-f0fbc2619237d255ac56e969c3bc4379889d25b0.jpg">
    </ul>
  </div>
</div>
