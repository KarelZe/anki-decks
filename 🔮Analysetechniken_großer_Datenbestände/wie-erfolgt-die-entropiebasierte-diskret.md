## Note
nid: 1605994939467
model: Basic-d7a3e
tags: 02_statistik, checklater
markdown: false

### Front
<p>Wie erfolgt die <b>entropiebasierte Diskretisierung</b>?

### Back
<p>Gegegeben Datenbestand \(S\) mit Attribut, entlang dessen diskretisiert werden soll.
</p><p>Partionierung von \(S\) in \(S_1\) und \(S_2\) mit Schwellenwert \(T\). </p><p>\(\operatorname{ Entropie }_{S p l i t}(S, T)=\frac{\left|S_{1}\right|}{|S|} \cdot \operatorname { Entropie }\left(S_{1}\right)+\frac{\left|S_{2}\right|}{|S|} \cdot \operatorname{ Entropie }\left(S_{2}\right)\)
</p><p>Man sucht also nach Abgrenzung, die o. g. Zielfunktion minimiert und wiederholt Berechnung rekursiv bis Abbruchkriterium erfüllt ist.</p>
