## Note
nid: 1602355385995
model: Basic-b122e
tags: 5_1_mpi
markdown: false

### Front
Was sind wesentliche Merkmale des Message Passing Paradigmas?

### Back
<ul>
<li>Auf jedem Prozessors in einem "message passing" Programm läuft genau ein Programm bzw. Prozess:
<ul>
<li>geschrieben in einer konventionellen Programmiersprache z. B. C</li>
<li>Typischerweise das gleiche Executable auf jedem Prozessor (SPMD)</li>
<li>Variablen im Programm bzw. Prozess haben denselben Name werden aber an unterschiedlichen Speicherstellen mit unterschiedlichen Daten abgelegt (→ Distributed Memory!)</li>
<li>Alle Variablen sind privat.</li>
<li>Austausch über Send & Recive Methoden des Message Passing Interfaces.</li>
</ul>
</li></ul>
