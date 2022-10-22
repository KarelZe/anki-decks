# Note
```
guid: I[[H_qPjBM
notetype: Basic-b122e-20a86
```

### Tags
```
3_4_prozesse_threads
```

## Front
Was ist eine <b>race condition</b>?

## Back
<b>Eigene Interpretation:</b> Ausgaben sollen unabhängig von den
Umständen des Wettrennens von Prozessoren bzgl. der Schnelligkeit
Zugriffsoperationen durchzuführen, um deterministische Ergebnisse
zu erhalten.
<div>
  <b>Folien Häfner:</b> Mindestens zwei threads greifen
  gleichzeitig auf die gleiche shared variable zu und zumindest 1
  thread modifiziert die Variable und die Zugriffe finden
  "gleichzeitig" und nicht synchronisiert statt (oftmals bei nicht
  beabsichtigtem Gebrauch von shared data).
</div>
