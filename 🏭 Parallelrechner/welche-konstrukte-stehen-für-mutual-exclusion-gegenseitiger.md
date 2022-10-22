# Note
```
guid: d}l``RO#Q;
notetype: Basic-b122e-20a86
```

### Tags
```
5_2_open_mp
```

## Front
Welche Konstrukte stehen für Mutual Exclusion (gegenseitiger Ausschluss) bei kritischen Abschnitten zur Verfügung?

## Back
<ul>
  <li>Kennzeichnung eines Abschnitts mit !$OMP CRITICAL (MAXLOCK).
  Dann kann nur ein Thread den kritischen Abschnitt zu einem
  Zeitpunkt betreten.
  <li>!$OMP ATOMIC gibt an, dass eine Speicheradresse atomar
  aktualisiert wird. Dient der Zuweisung von skalaren Variablen.
</ul>
