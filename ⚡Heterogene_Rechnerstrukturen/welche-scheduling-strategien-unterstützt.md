## Note
nid: 1613859902863
model: Basic-b122e
tags: 06_mpi_openmp
markdown: false

### Front
Welche <b>Scheduling-Strategien</b> unterstützt OpenMP?

### Back
<div>
  <div>
    <ul>
      <li>
        <strong>static</strong>
        <ul>
          <li>Arbeitspakete werden gleichmäßig an Threads verteilt
          <li>vorteilhaft, wenn jede Iteration gelich viel Zeit
          benötigt
        </ul>
      <li>
        <strong>dynamic</strong>
        <ul>
          <li>Threads holen dynamisch bei Bedarf neues Arbeitspaket
          <li>vorteilhaft, wenn Iterationen utnerschiedlich viel
          Zeit benötigen → Lastbalancierung
        </ul>
    </ul>
  </div>
</div>
