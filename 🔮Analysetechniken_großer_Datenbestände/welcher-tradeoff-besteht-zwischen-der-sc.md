## Note
nid: 1632853216035
model: Basic-d7a3e
tags: 08_constrained_ar, checklater
markdown: false

### Front
Welcher <b>Tradeoff</b> besteht zwischen der Schärfe von
Constraints?

### Back
Ist \(\mathcal{R}\) extrem selektiv (und nicht anti-monoton), dann
funktioniert Constraint-basiertes Pruning offensichtlich gut.
<div>
  Support-basiertes Pruning aber nicht. Support-basiertes Pruning
  betrachtet alle Teilstrukturen der Größe \(k-1\) in \(L_{k+1}\),
  wovon nur noch wenige Strukturen verbleiben.
</div>
