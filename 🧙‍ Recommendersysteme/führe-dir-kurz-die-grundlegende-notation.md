## Note
nid: 1588096670752
model: Basic-b122e-20a86
tags: 02_assoziationsregeln
markdown: false

### Front
Führe dir kurz die grundlegende Notation für Assoziationsregeln vor Augen:

### Back
Wir betrachten eine Menge \(I=i_{1}, i_{2}, \ldots, i_{m}\) von ltems
 \(\rightarrow\) Produkte, URLs, Webseiten<div>
eine Reihe  \(T=\left(t_{1}, t_{2}, \ldots, t_{n}\right)\) von Transaktionen mit  \(t_{j} \subseteq I\)
 \(\rightarrow\) Warenkorb, Session</div><div>
Wir suchen nun häufige Assoziationsregeln  \(X \rightarrow Y\)
wobei  \(X \subseteq I\) und  \(Y \subseteq I\).</div><div>
<b>Interpretation:</b></div><div>Wenn alle in  \(X\) enthaltenen Artikel im Warenkorb sind, dann werden häufig auch Artikel aus  \(Y\) gekauft. D.h. Wenn ein Kunde die Menge  \(X\) gekauft hat, dann empfiehl ihm  \(Y\).</div>
