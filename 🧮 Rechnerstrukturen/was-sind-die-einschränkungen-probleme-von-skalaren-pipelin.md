# Note
```
guid: csChe$~a$x
notetype: Basic-d7a3e-4ce08
```

### Tags
```
06_para_maschinenbefehl
checklater
klausur
```

## Front
Was sind die <b>Einschränkungen</b> / Probleme von <b>skalaren
Pipelines</b>?

## Back
<div>
  <ul>
    <li>max wird 1 Anweisung pro Takt ausgeführt.
    <li>Eine wartende Anweisung verursacht eine angehaltene
    Pipeline (<em>pipeline stall</em>), sodass nachfolgende Befehle
    ebenfalls warten müssen (<em>backward propagation of
    stalling</em>)
  </ul>
</div>
