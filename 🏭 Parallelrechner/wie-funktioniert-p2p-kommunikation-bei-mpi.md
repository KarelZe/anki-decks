# Note
```
guid: g#AR*@?$?H
notetype: Basic-b122e-20a86
```

### Tags
```
5_1_mpi
```

## Front
Wie funktioniert P2P-Kommunikation bei MPI?

## Back
<ul>
  <li>Kommunikation zwischen zwei Prozessen, wovon einer sendet und
  ein anderer empfängt.
  <li>Kommunikation passiert innerhalb eines Kommunikators
  (MPI_COMM_WORLD).
  <li>Prozesse werden durch ranks identifiziert.
  <li>Befehl zum Senden ist MPI_SEND(...) Parameter sind buf =
  erstes Element der Botschaft, ein tag mit nicht-negativer
  Information z. B. Nachrichtenart dest = rank vom Ziel.
  <li>Befehl zum Empfanngen ist MPI_RECV(...) Parameter sind
  Empfangspuffer, Umschlagsinformationen, Ausgabeargumente, tag)
  <li>Für erfolgreiche Kommunikation muss:
    <ul>
      <li>rank passen
      <li>Kommunikator gleich sein (Wildcards möglich)
      <li>tags übereinstimmen (Wildcards möglich)
      <li>Datentyp der Botschaft übereinstimmen.
      <li>Empfangspuffer ausreichend groß sein.
    </ul>
</ul>
<div><img src="paste-a960eb99592963886b6cf80ad3a396cf5ed5496e.jpg"></div>
