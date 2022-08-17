## Note
nid: 1602355294658
model: Basic-b122e
tags: 5_1_mpi
markdown: false

### Front
Wie erfolgt die Daten- und Arbeitsverteilung bei MPI?

### Back
<ul>
  <li>Es existiert eine Variable rank, die von einer MPI
  Bibliotheksroutine festgelegt wird.
  <li>Alle size Prozesse werden durch ein MPI
  Initialisierungsprogramm gestartet.
  <li>Alle Verteilungsentscheidungen basieren auf dem rank d. h.
  welche Prozesse auf welchen Daten operieren.
  <li><img src=
  "paste-044c66045025b6a0d954212935552f3fe46d8256.jpg">
</ul>
