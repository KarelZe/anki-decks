# Note
```
guid: d]KFKa5].f
notetype: Basic-d7a3e-4ce08
```

### Tags
```
04_koheraenz
11_para_block_prozess
```

## Front
Wie lässt sie das Konzept von <b>sequentieller Konsistenz</b>
<b>veranschaulichen</b>?

## Back
Welcher Thread Zugriff auf den gemeinsamen Speicher beim
Programmablauf hat, ist vergleichbar mit einem Schalter.
<div><img src="54244817.png"></div>
<div>
  <ol>
    <li>Jeder Thread führt seine Zugriffe auf den gemeinsamen
    Speicher eins nach dem anderen in der Thread Ordnung aus.
    <li>Zu einem Zeitpunkt erfolgt nur ein Zugriff auf den
    gemeinsamen Speicher.
    <li>Da der Schalter immer nur einem Thread zugewiesen ist,
    werden Speicherzugriffe atomisch sichtbar.
  </ol>
</div>
