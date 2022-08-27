## Note
nid: 1589974680944
model: Basic-b122e-20a86
tags: 2_6_parallelrechner
markdown: false

### Front
Wie funktioniert Pipelining bei Vektorrechnern?

### Back
<b style="">Pipelining-Prinzip</b>
<div>
  <ul>
    <li>Nächste Gleitkommaoperation kann schon vor Beendigung der
    vorherigen Operation gestartet werden. Teilrechenwerke sind in
    Stufen angeordnet
    <li>Voraussetzung sind genügend gleichartige
    Verarbeitungsaufträge
    <li>Die Vektoren werden sequentiell und überlappend
    abgearbeitet, d.h. zuerst wird die Berechnung B(1)+C(1)
    gestartet, dann B(2)+C(2), usw.
    <li>Pipeline-Verarbeitung wird mit einem <b>Vektorbefehl</b>
    für zwei Felder von Gleitpunktzahlen durchgeführt.
    <li>Bei ununterbrochener Arbeit in der Pipeline kann man nach
    einer gewissen <b>Einschwingzeit</b> bzw. <b>Füllzeit</b>, die
    man braucht, um die Pipeline zu füllen, mit jedem Pipeline Takt
    ein Ergebnis erwarten.
    <li>Dabei ist die Taktdauer durch die Dauer der längsten
    <b>Teilverarbeitungszeit zuzüglich der Stufentransferzeit</b>
    gegeben.
  </ul>
  <div><img src=
  "paste-2939ba7e114a9f36a5f7d4bbb890132e5487980d.jpg"></div>
</div>
