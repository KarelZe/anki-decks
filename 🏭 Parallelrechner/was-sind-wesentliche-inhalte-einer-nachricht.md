# Note
```
guid: _6Ecz`|<T
notetype: Basic-b122e-20a86
```

### Tags
```
3_6_synchronisation_und_kommunikation
```

## Front
Was sind wesentliche Inhalte einer Nachricht?

## Back
<ul>
  <li><b>Ziel der Nachricht</b> (z. B. Prozess, Knoten,
  Empfangskanal)
  <li><b>Nachrichtennummer</b> zur Identifikation der Nachricht
  <li><b>Speicherbereich</b>, dessen Inhalt in der Nachricht
  verschickt werden soll (z. B. meist durch Angabe eines Zeigers
  auf eine Variable, die als Sendepuffer dient)
  <li><b>Anzahl und Datentypen</b> der einzelnen Datenelemente im
  Sendepuffer, die verschickt werden sollen. Dies wird zur
  Berechnung der korrekten Nachrichtenlänge gebraucht.
</ul>
<div>
  <b>Aus Kapitel zu MPI</b>
  <ul>
    <li>Sendender / Empfangender Prozess
    <li>Lokation der Quelle / des Ziels
    <li>Datentyp der Quelle / des Ziels
    <li>Datengröße der Quelle / des Ziels
  </ul>
</div>
