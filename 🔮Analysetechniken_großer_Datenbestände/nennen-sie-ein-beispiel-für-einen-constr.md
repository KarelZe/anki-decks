## Note
nid: 1611050416345
model: Basic-d7a3e
tags: 08_constrained_ar, checklater
markdown: false

### Front
<p>Nennen Sie ein Beispiel für einen Constraint, der <b>nicht
anti-monoton</b> ist für die Folge <span>abababab.</span>

### Back
<p>Regulärer Ausdruck (ab)* ist nicht antimonoton.
<p><span style="letter-spacing: 0.01071em;">Da aaaa Teilfolge
von</span> <span>abababab ist. Der Constraint / Reguläre Ausdruck
"greift" aber für Teilmenge nicht. Ist damit nicht
anti-monton.</span>
<p>Beim Mining wäre es egal, ob die Folge aab möglicherweise
frequent ist, da sie bereits beim <b>Constraint-basierten
Pruning</b> raus fliegt, das vor dem <b>Support-basierten
Pruning</b> passiert. Ggf. kann aber bei anti-monotonen Folgen
passieren, dass Constraint für Teilfolge nicht erfüllt ist, dieser
aber für die Ausgangsfolge halten würde. Bisheriges Vorgehen
funktioniert nicht!
