## Note
nid: 1602354991795
model: Basic-b122e
tags: 5_1_mpi
markdown: false

### Front
Was sind Kommunikatoren bei MPI? Welche beiden Arten unterscheidet man?

### Back
<ul>
<li>MPI_COMM_WORLD ist ein Kommunikator, der alle Prozesse vereinigt, und von MPI vordefiniert.</li>
<li>Aus einer Prozessgruppe lassen sich Untergruppen bilden, welche mit MPI_Comm_Create ein neuer Kommunikator erzeugen kann.</li>
<li>Kommunikatoren beschränken eine Nachricht auf Ihren Kontext z. B Subroutinen, welche ausgeführt werden.</li>
<li>Verschiedene Topologien z. B. Gitter bei Kommunikatoren möglich.</li>
<li><strong>Zwei Arten</strong>
<ul>
<li>Der sogeannnte Intra-Kommunikator ist innerhalb einer Prozessgruppe / Topologie definiert und kann für kollektive Operationen verwendet werden.</li>
<li>Einer Inter-Kommunikator betrifft zwei Proezssgruppen und wird für die Punkt-zu-Punkt Kommunikation zwischen zwei Prozessgruppen eingesetzt.</li>
</ul>
</li></ul>
