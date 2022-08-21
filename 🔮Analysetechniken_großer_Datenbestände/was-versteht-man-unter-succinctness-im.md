## Note
nid: 1608984948414
model: Basic-d7a3e
tags: 08_constrained_ar, checklater
markdown: false

### Front
<p>

Was versteht man unter <strong>Succinctness</strong> im Zusammenhang mit <b>Constraints</b>?


</p>

### Back
<ul style="letter-spacing: normal; text-indent: 0px; 
 text-transform: none; white-space: normal; word-spacing: 0px;">
  <li style="font-weight: 400;"><em>Succinctness</em> ist eine
  Eigenschaft von Constraints.
  <li style="font-weight: 400;">Constraints sind succinct, wenn man
  alle Itemsets, die das Constraint erfüllen, explizit "in kurzer
  Art und Weise" hinschreiben kann.
  <li style="">z. B. <i style="font-weight: 400;">Constraint =
  S.Type ={Nonfood}</i>, sofern nur 3 Non-Food Artikel im Sortiment
  sind. Damit gäbe es 7 Kombinationen (\(2^3 -1\)). Hierfür
  bestimmt man die Anzahl der Vorkommen (<b>Support Counting</b>)
  durch mit einem Gang über die Datenbank. Man braucht keinen
  klassischen Apriori.
</ul>
<div>
  <div>
    <b>Ng et al. Alternative Definition:</b>
  </div>
  <div>
    Itemset ist ein succinct set, wenn für alle Items darin
    festegestellt werden kann (mittels einer Abfrage der DB), ob
    sie Constraint erfüllen.
  </div>
  <div>
    Wenn wir also für jedes Item wissen, ob es Constraint erfüllt,
    dann können wir davon alle gültigen Itemsets ableiten (ohne
    jedes Mal über die DB zu müssen).
  </div>
</div>
<div>
  <b>Beispiele</b>:
</div>
<div><img src=
"paste-2d1fd60a353275f461a8408417e2d1e82081a10b.jpg"></div>
<div>
  <b>Beispiele für succint:</b>
</div>
<div>
  Sei \(S\) eine Menge an Attributwerten in einem Itemset, z. B.
  die Preise der Items, und sei \(v\) ein fester (aber beliebiger)
  Wert.
</div>
<div>
  \(\min (S) \leq v, \min (S) \geq v, \min (S)=v\) Wenn ich für
  zwei Items / Itemsets weiß, ob Constraint erfüllt, dann weiß ich
  es auch für Vereinigung, ohne mir die Attributwerte noch einmal
  anzuschauen.
</div>
<div>
  Wenn in einem Itemset \(\min \left(S_{1}\right) \leq 4\)
  (Constraint erfüllt) und in anderem \(\min \left(S_{2}\right)
  \leq 4\) (Constraint erfüllt), dann \(\min \left(S_{1} \cup
  S_{2}\right) \leq 4\) (Constraint erfüllt)
</div>
<div>
  Wenn in einem Itemset \(\min \left(S_{1}\right) \leq 4\)
  (Constraint erfüllt) und in anderem \(\min \left(S_{2}\right)
  \not \leq 4\) (Constraint verletzt), dann \(\min \left(S_{1} \cup
  S_{2}\right) \leq 4\) (Constraint erfüllt)
</div>
<div>
  Wenn in einem Itemset \(\min \left(S_{1}\right) \not \leq 4\)
  (Constraint verletzt) und in anderem \(\min \left(S_{2}\right)
  \not \leq 4\) (Constraint verletzt), dann \(\min \left(S_{1} \cup
  S_{2}\right) \not \leq 4\) (Constraint verletzt)
</div>
<div>
  In allen Fällen kann also hergeleitet werden, ob Constraint
  erfüllt ist
</div>
<div>
  <b>Gegenbeispiele:</b>
</div>
<div>
  Gegenbeispiel für succinct: \(\operatorname{sum}(S) \leq v,
  \operatorname{sum}(S) \geq v, \operatorname{sum}(S)=v\) Wenn in
  einem Itemset \(\operatorname{sum}\left(S_{1}\right) \leq 4\)
  (Constraint erfüllt) und in anderem
  \(\operatorname{sum}\left(S_{2}\right) \leq 4\) (Constraint
  erfüllt), dann weiß ich nicht, ob Constraint für Vereinigung
  erfüllt (hängt von konkreten Attributwerten ab). Wenn dagegen in
  einem der beiden Itemsets Constraint verletzt, dann auch immer in
  Vereinigung. Insgesamt also nicht immer (ohne Rückgriff auf
  Attributwerte) Aussage möglich, ob Vereinigung der Itemsets die
  Constraint erfüllt \(\rightarrow\) nicht succint.
</div>
