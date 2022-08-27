## Note
nid: 1602347202186
model: Basic-b122e-20a86
tags: Eigene
markdown: false

### Front
Wie lassen sich Deadlocks verhindern?

### Back
<ul>
  <li><strong>Preemption durchführen</strong> Einem Prozess werden
  die Betriebsmittel entzogen, um sie einem anderen Prozess
  zuzuteilen.
  <li><strong>Hold and wait verhindern</strong> Jeder Prozess gibt
  zu Beginn an, welche Betriebsmittel er benötigt. Falls alle
  benötigte Betriebsmittel gleichzeitig frei sind, bekommt sie ein
  Prozess auf einmal zugeteilt.
  <li><strong>Mutual Exclusion beseitigen</strong> Die benötigten
  Betriebsmittel für alle Prozesse zugänglich zu machen, indem man
  den exklusiven Zugang auflöst z. B. Spooling, Virtualisierung von
  Betriebsmitteln.
  <li><strong>Circular Wait ausschließen</strong> Betriebsmittel
  werden linear angeordnet und in festgelegter Reihenfolge
  verarbeitet
</ul>
