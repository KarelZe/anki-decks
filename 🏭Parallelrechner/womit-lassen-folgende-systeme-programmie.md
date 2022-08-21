## Note
nid: 1602347101988
model: Basic-b122e
tags: Eigene
markdown: false

### Front
<h3>Womit lassen folgende Systeme programmieren?</h3>
<ul>
  <li>Parallelrechner mit <strong>verteiltem Speicher</strong> in
  vielen Rechnerknoten: <font color="#FFAA00">...</font>
  <li>Rechnerknoten mit Multi-Core-Prozessoren und gemeinsamen
  Adressraum und Speicher: Synchronisation und Kommunikation über
  gemeinsamen Variablen: <font color="#FFAA00">...</font>
  <li>SMP Rechnerknoten mit Beschleunigern (GPUs, FPGAs,...)
  <li>Auslagern spezieller Programmteile auf
  <strong>Beschleuniger</strong>: <font color="#FFAA00">...</font>
</ul>

### Back
<ul><li>Parallelrechner mit <strong>verteiltem Speicher</strong> in vielen Rechnerknoten: MPI</li>
<li>Rechnerknoten mit Multi-Core-Prozessoren und gemeinsamen Adressraum und Speicher: Synchronisation und Kommunikation über gemeinsamen Variablen: OpenMP und Pthreads (= POSIX Threads)</li>
<li>SMP Rechnerknoten mit Beschleunigern (GPUs, FPGAs,...)</li>
<li>Auslagern spezieller Programmteile auf <strong>Beschleuniger</strong>: CUDA, OpenCL, OpenACC</li></ul>
