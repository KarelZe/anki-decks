# Note
```
guid: M!CV=,)mzj
notetype: Basic-d7a3e-4ce08
```

### Tags
```
06_programmiermodelle
```

## Front
Erklären Sie wie die Parallelisierungsstrategie <b>Pipeline
(Producer / Consumer)</b> funktioniert.

## Back
<ul>
  <li>
    <div>
      Nachrichten werden von einem Prozess / Thread zum nächsten
      geschickt.
    </div>
  <li>
    <div>
      <strong>Beispiel</strong>: Bildverarbeitung, z. B. zuerst
      Weißabgleich, dann Filter, dann Reduzierung
    </div>
</ul>
<div>
  <b>Visualisierung der aufeinanderfolgenden Threads:</b>
</div><img src="28334820.png">
<div>
  Ist T1 mit Abarbeitung fertig, kann er sich neuem Task widmen.
</div>
