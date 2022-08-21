## Note
nid: 1611050417365
model: Basic-d7a3e
tags: 08_constrained_ar
markdown: false

### Front
<p>Wie erfolgt <b>Constraint-basiertes Pruning</b> bei <b>Teilfolgen</b>?</p>

### Back
<p>Schritt \(k\) generiert \(L_{k}\). \(L_{k}\) - Menge der
häufigen k-Folgen, die Constraint \(\mathcal{R}\) erfüllen.
<p><b>Illustration:</b>
<p><img src="paste-d4b1416db92f3e2c8cfcaa6653b055524ead9ae4.jpg">
<p><span>Wenn man beim Durchlaufen der Kanten am Endzustand
(doppelter Kringel) rauskommt, dann ist alles gut und Constraint
erfüllt. z. B. 3, 2, 1 ist Folge, die Constraint nicht erfüllt,
weil keine Kante 3 von a ausgeht.</span>
