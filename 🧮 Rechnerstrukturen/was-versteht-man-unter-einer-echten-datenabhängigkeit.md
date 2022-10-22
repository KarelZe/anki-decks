# Note
```
guid: @p9.<ULS8
notetype: Basic-d7a3e-4ce08
```

### Tags
```
06_para_maschinenbefehl
```

## Front
Was versteht man unter einer <b>echten Datenabhängigkeit</b>?

## Back
Ein Befehl \(j\) ist datenabhängig von einem Befehl \(i\), wobei
der Befehl \(i\) im Programm vor dem Befehl \(j\) steht, wenn
Folgendes gilt:
<div>
  <ul>
    <li>Befehl \(i\) produziert Ergebnis, das von \(j\) verwendet
    wird oder
    <li>Befehl \(j\) ist datenabhängig von Befehl \(k\) und Befehl
    \(k\) ist datenabhängig von Befehl \(i\) (Abhängigkeitskette)
  </ul>
</div>
