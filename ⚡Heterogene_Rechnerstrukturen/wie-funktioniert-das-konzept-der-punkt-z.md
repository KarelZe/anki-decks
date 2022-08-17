## Note
nid: 1613918622804
model: Basic-b122e
tags: 06_mpi_openmp
markdown: false

### Front
Wie funktioniert das <b>Konzept</b> der
<b>Punkt-zu-Punkt-Kommunikation</b>?

### Back
<div>
<div><ul>
<li>Arbeit wird zwischen zwei Tasks aufgeteilt, die Daten per Nachrichtenaustausch kommunizieren.</li>
<li>Ein Task ist Sender und führt Send-Operation aus.</li>
<li>Ein Task ist Empfänger und führt korrespondierende Recv-Operation aus.</li>
</ul>
</div></div>
