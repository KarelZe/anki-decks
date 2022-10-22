# Note
```
guid: jBMz[J(T9S
notetype: Basic-d7a3e-4ce08
```

### Tags
```
05_verteilter_speicher
11_para_block_prozess
```

## Front
Was ist der Nachteile von synchronem Message Passing?

## Back
Die Kombination von Synchronisation und Kommunikation in einer
Primitive kann zu <b>Leistungsverlust</b> führen. Es handelt sich
bei Synchronisation und Kommunikation beides Mal um langlaufende
Operationen, sie beide in ein Primitiv zu packen führt also zu
Leistungsverslusten.
<div>
  Keine Überlappung von Kommunikation und Berechnung.
</div>
<div>
  Fehleranfällig für Deadlocks.
</div>
