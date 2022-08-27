## Note
nid: 1613920543130
model: Basic-d7a3e-4ce08
tags: 06_mpi_openmp
markdown: false

### Front
Was wird bei <b>MPI </b>im <b>Systempuffer</b> abgelegt?

### Back
<div>
<div><ul>
<li>Ein Systempufferbereich ist dafür reserviert, die zu übertragenden Daten zu puffern.</li>
<li>Ermöglicht asynchrone Kommunikation.</li>
<li>Verwaltet von der MPI Bibliothek.</li>
<li>Nicht sichtbar für Programmierer.</li><li>Vergleichsweise hoher Aufwand zwischen Anwendungs- und Systempuffer zu kopieren.</li></ul></div></div><img src="79760899.png">
