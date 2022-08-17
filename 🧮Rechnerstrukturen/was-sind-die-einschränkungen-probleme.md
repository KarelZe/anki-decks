## Note
nid: 1628164168708
model: Basic-d7a3e
tags: 06_para_maschinenbefehl, checklater, klausur
markdown: false

### Front
Was sind die <b>Einschränkungen</b> / Probleme von <b>skalaren
Pipelines</b>?

### Back
<div>
  <ul>
    <li>max wird 1 Anweisung pro Takt ausgeführt.
    <li>Eine wartende Anweisung verursacht eine angehaltene
    Pipeline (<em>pipeline stall</em>), sodass nachfolgende Befehle
    ebenfalls warten müssen (<em>backward propagation of
    stalling</em>)
  </ul>
</div>
