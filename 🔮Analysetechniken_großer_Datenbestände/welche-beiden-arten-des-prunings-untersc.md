## Note
nid: 1608984943346
model: Basic-d7a3e
tags: 08_constrained_ar
markdown: false

### Front
<p>Welche beiden Arten des <b>Prunings</b> unterscheidet man?
(Nicht Pre / Post-Pruning)

### Back
<ul style= 
"font-weight:400;letter-spacing:normal;text-indent:0px;text-transform:none;white-space:normal;word-spacing:0px">
  <li><strong>Support-basiertes</strong> - Kandidat wird
  eleminiert, wenn er selbst (oder bereits in seiner Teilmenge)
  nicht frequent ist. (vgl. prune / support counting Schritt)
  <li><strong>Constraint-basiertes</strong> - Kandidat wird
  eleminiert, wenn er ein Constraint nicht erfüllt.
  <li>Zwischen beiden besteht ein Trade-off (wenn z. B. durch
  Constraints weniger Support-basiertes Pruning möglich.)
</ul>
<div>
  <b>Beispiel für Pruning:</b>
</div>
<div>
  Filzstift im Supermarkt.
</div>
<div>
  Item „Filzstift“ vermutlich nur in wenigen Transaktionen,
  insofern geringer Support Constraint „Type=Non-Food“ ist von
  {Filzstift} erfüllt, aber vermutlich auch von anderen Item(set)s
  (mit womöglich größeren Support; insofern unklar, wie stark
  Pruning durch die Constraint allein ist) <b>Support-basiertes
  Pruning</b> unter Berücksichtigung der Constraint: untersuche nur
  Itemsets bestehend aus Non-Food-ltems und prune, wenn Item
  „Filzstift" enthalten
</div>
