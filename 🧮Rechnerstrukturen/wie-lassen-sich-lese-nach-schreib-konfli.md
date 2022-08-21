## Note
nid: 1628186562459
model: Basic-d7a3e
tags: 06_para_maschinenbefehl
markdown: false

### Front
Wie lassen sich <b>Lese-nach-Schreib-Konflikte</b>
<i>(Read-After-Write, RAW)</i> auflösen?

### Back
Mittels eines Umordnungspuffers. Jede Ausführungseinheit oder
mehrere Ausführungseinheiten gemeinsam teilen sich einen
<b>Umordnungspuffer</b>.
<div>
  Zuordnung eines Befehls an Umordnungspuffer kann nur erfolgen,
  wenn ein freier Platz vorhanden ist, ansonsten müssen die
  nachfolgenden Befehle warten.
</div>
