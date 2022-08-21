## Note
nid: 1613920543130
model: Basic-b122e
tags: 06_mpi_openmp
markdown: false

### Front
Was wird bei <b>MPI</b> im <b>Systempuffer</b> abgelegt?

### Back
<div>
  <div>
    <ul>
      <li>Ein Systempufferbereich ist dafür reserviert, die zu
      übertragenden Daten zu puffern.
      <li>Ermöglicht asynchrone Kommunikation.
      <li>Verwaltet von der MPI Bibliothek.
      <li>Nicht sichtbar für Programmierer.
      <li>Vergleichsweise hoher Aufwand zwischen Anwendungs- und
      Systempuffer zu kopieren.
    </ul>
  </div>
</div><img src="79760899.png">
