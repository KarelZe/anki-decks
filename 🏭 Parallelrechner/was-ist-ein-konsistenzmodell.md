# Note
```
guid: eMOsJGJvzy
notetype: Basic-b122e-20a86
```

### Tags
```
Eigene
```

## Front
Was ist ein Konsistenzmodell?

## Back
<ul>
  <li>Im Prinzip ein Vertrag zwischen einem Datenspeicher und den
  darauf zugreifenden Prozessen
  <li>"Wenn sich die Prozesse an gewisse Regeln halten, arbeitet
  der Datenspeicher korrekt"
  <li>Grundsätzlich soll ein Read den Wert des letzten Write
  zurückliefern. In Abwesenheit einer <b>globalen Uhr</b> ist
  unklar, was das ist. Deshalb werden Konsistenzmodelle gebraucht!
</ul>
