## Note
nid: 1601805032561
model: Basic-b122e
tags: Eigene
markdown: false

### Front
Was ist ein Konsistenzmodell?

### Back
<ul>
  <li>Im Prinzip ein Vertrag zwischen einem Datenspeicher und den
  darauf zugreifenden Prozessen
  <li>"Wenn sich die Prozesse an gewisse Regeln halten, arbeitet
  der Datenspeicher korrekt"
  <li>Grundsätzlich soll ein Read den Wert des letzten Write
  zurückliefern. In Abwesenheit einer <b>globalen Uhr</b> ist
  unklar, was das ist. Deshalb werden Konsistenzmodelle gebraucht!
</ul>
