# Note
```
guid: pzbm,NKZ(D
notetype: Basic-9c783
```

### Tags
```
datenschutz::07_secure_multiparty
```

## Front
Beurteilen Sie das <b>private Skalarprodukt</b> hinsichtlich
<b>Sicherheit</b> und <b>Performanz</b>.

## Back
<b>Protokoll ist performant:</b> Braucht nur 4
Kommunikationsvorgänge pro Berechnung eines Skalarprodukts, was
über einen Vektor wenig ist. <b>Protokoll ist sicher:</b> Angreifer
müsste\(k\) Gleichungen mit mehr als \(k\) Unbekannten lösen.
<b>Ergebnisse ableitbar:</b> Aus vertikal prationierten Daten sind
Informationen aus Ergebnis ableitbar. Ist z. B. das Skalarprodukt
aus zwei Vektoren 1, dann lernt die eine Parte, dass die andere
Partei dort im Vektor eine Null stehen haben muss.
