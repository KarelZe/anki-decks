## Note
nid: 1609430840125
model: Basic-d7a3e
tags: 03_raeumliche_index_strukturen, checklater
markdown: false

### Front
<p>Wie findet man bei <b>Bereichsanfragen </b>alleDatenobjekte innerhalb des Bereichs?</p>

### Back
<p>Man steigt bei Wurzel ein. Am ersten Split frägt man sich ob man
Überlappung mit (--, 6) oder (--,4) hat, dann steigt man jeweils
nach unten. Man prüft also, ob der Raum den man abfrägt eine
Überlappung mit dem Split des akutellen Knotens hat, oder nicht.
<p>Man steigt bei (--, 6) nach unten, dann nach (4,--)... . Es
reicht in einen Teilbaum abzusteigen, falls Bereich nur in eine
Hälfte des Splits fällt. Fällt ein Split in Bereich der Anfrage, so
steigt man in beide Teilbäume hinab.
<p>Auf Blattebene überprüft man dann für jedes einzelne Objekt, ob
es im Bereich liegt und gibt das Ergebnis zurück.
<p><img src="1vET2yLfQs95XoFCxs5F.png" style="width: 366px;">
