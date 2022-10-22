# Note
```
guid: Inl+IEqGxe
notetype: Basic-9c783
```

### Tags
```
datenschutz::09-blockchain
```

## Front
Was bedeutet <b>Integrität </b>in der <b>Blockchain</b>? Wie steht sie im Kontrast zur Integrität bei DBs?

## Back
<b>Integrität in Datenbanken:
Referentielle Integrität:</b> Fremdschlüssel müssen auf existierende Tupel verweisen
<b>Statische Integritätsbedingungen:</b> Wertebereichsgrenzen, Unique-Eigenschaften, NOT-NullEigenschaften
<b>Semantische Integritätsbedingungen:</b> anwendungsabhängig, z.B.: Gehalt darf bei einem Update nur größer werden, Termine niemals kleiner als aktuelles Datum, etc.

<b>Integrität in der Blockchain:</b> 
Integritätsbedingungen für die Blöcke
<b>statische Integrität:</b> protokollgerecht ausgefüllte Datenfelder, Nonce ist eine gültige Lösung für Challenge + Restriction, Account ist nicht Null...
<b>semantische Integrität:</b> kein Double Spending (digitale Objekte aus einer Transaktion können nur einem Teilnehmer gehören), Zeitstempel jünger als der vom Vorgängerblock, etc.
