# Note
```
guid: hNdTEP8qKA
notetype: Basic-9c783
```

### Tags
```
datenschutz::06_private_db
temp
```

## Front
Warum ist die <b>Partionierung</b> und <b>Rechtverteilung</b> nicht
ausreichend um vor <b>Zugriff des Server-Betreibers</b> zu
schützen?

## Back
<ul>
  <li>Physische Aufteilung der Daten, d. h., man kann sicherstellen
  dass sensible Daten an einem bestimmten Speicherort bleiben
  <li><b>Feingranulares Rechtemanagement</b>
  <li><b>Verteilte Anfrageausführung:</b> passende Zugriffsrechte
  vorausgesetzt, verschickt DBMS sensible Teilergebnisse
</ul>=> Serverbetreiber sieht die Fragmente in seinem
Einflußbereich.
