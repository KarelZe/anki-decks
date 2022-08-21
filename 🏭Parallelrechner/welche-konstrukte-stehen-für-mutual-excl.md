## Note
nid: 1602352564098
model: Basic-b122e
tags: 5_2_open_mp
markdown: false

### Front
Welche Konstrukte stehen für Mutual Exclusion (gegenseitiger Ausschluss) bei kritischen Abschnitten zur Verfügung?

### Back
<ul>
  <li>Kennzeichnung eines Abschnitts mit !$OMP CRITICAL (MAXLOCK).
  Dann kann nur ein Thread den kritischen Abschnitt zu einem
  Zeitpunkt betreten.
  <li>!$OMP ATOMIC gibt an, dass eine Speicheradresse atomar
  aktualisiert wird. Dient der Zuweisung von skalaren Variablen.
</ul>
