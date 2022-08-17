## Note
nid: 1632844991342
model: Basic-d7a3e
tags: 08_constrained_ar, checklater, ultra
markdown: false

### Front
Was sind zwei gutartige / wünschenswerte <b>Eigenschaften </b>von <b>Constraints</b>?

### Back
<div>
  <span style="font-weight: bold;">Anti-Monotonizität:</span>
</div>
<div>
  <span style="text-decoration-line: underline;">Ziel:</span>
  Constraint möglichst früh überprüfen und Pruning so früh wie
  möglich stattfinden lassen.
</div>
<div>
  <span style="text-decoration-line: underline;">Defintion:</span>
  Ein Constraint ist anti-monoton gdw. für alle Mengen S, S' gilt:
  Wenn das Constraint für die Obermenge erfüllt ist, ist es auch
  für die Teilmenge erfüllt.
</div>
<div>
  <strong>Succinctness:</strong>
</div>
<div>
  <span style="text-decoration-line: underline;">Ziel:</span>
  Kandidaten, die Constraint nicht erfüllen, werden gar nicht erst
  erzeugt
</div>
<div>
  <span style="text-decoration-line: underline;">Definition:</span>
  Constraint ist succinct, wenn man alle Itemsets, die das
  Constraint erfüllen explizit in kurzer Art und Weise hinschreiben
  kann
</div>
