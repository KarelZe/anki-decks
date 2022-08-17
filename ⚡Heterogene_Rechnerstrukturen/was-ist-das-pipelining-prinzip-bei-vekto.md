## Note
nid: 1613743924131
model: Basic-b122e
tags: 07_vektorprozessoren, 12_Vektorverarbeitung
markdown: false

### Front
Was ist das <b>Pipelining-Prinzip</b> bei <b>Vektorrechnern</b>?

### Back
<ul>
  <li>Nächste Gleitkommaoperation kann schon vor Beendigung der
  vorherigen Operation gestartet werden. Teilrechenwerke sind in
  Stufen angeordnet
  <li>Die Vektoren werden sequentiell und überlappend abgearbeitet,
  d.h. zuerst wird die Berechnung B(1)+C(1) gestartet, dann
  B(2)+C(2), usw.
  <li>Pipeline-Verarbeitung wird mit einem <b>Vektorbefehl</b> für
  zwei Felder von Gleitpunktzahlen durchgeführt.
  <li>Bei ununterbrochener Arbeit in der Pipeline kann man nach
  einer gewissen <b>Einschwingzeit</b> bzw. <b>Füllzeit</b>, die
  man braucht, um die Pipeline zu füllen, mit jedem Pipeline Takt
  ein Ergebnis erwarten.
  <li>Dabei ist die Taktdauer durch die Dauer der längsten
  <b>Teilverarbeitungszeit zuzüglich der Stufentransferzeit</b>
  gegeben.
</ul><img src="paste-2939ba7e114a9f36a5f7d4bbb890132e5487980d.jpg">
