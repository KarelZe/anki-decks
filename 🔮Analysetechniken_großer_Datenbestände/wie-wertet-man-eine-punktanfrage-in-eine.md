## Note
nid: 1609430842034
model: Basic-d7a3e
tags: 03_raeumliche_index_strukturen, checklater
markdown: false

### Front
<p>Wie wertet man eine <b>Punktanfrage</b> in einem <b>kd-Baum</b> für Objekte mit <b>räumlicher Ausdehnung</b> aus? Vollziehen Sie dafür nachfolgendes Beispiel nach.</p>

### Back
<p style= 
"font-weight:400;letter-spacing:0.12852px;text-indent:0px;text-transform:none;white-space:normal;word-spacing:0px">
Jedes Rechteck ist ein vierdimensionaler Punkt wegen oberem linken
Eck und unterem rechten Eck.
<p style= 
"font-weight:400;letter-spacing:0.12852px;text-indent:0px;text-transform:none;white-space:normal;word-spacing:0px">
Punkt wird also beschrieben durch (links, rechts, oben, unten).
<p style="letter-spacing: 0.12852px; text-indent: 0px; 
 text-transform: none; white-space: normal; word-spacing: 0px;">
<b>Beispiel:</b>
<p style="letter-spacing: 0.12852px; text-indent: 0px; 
 text-transform: none; white-space: normal; word-spacing: 0px;">
<img src="paste-8e9027df2d547a120171a36c520018c5bd3c5de9.jpg">
<p style= 
"font-weight:400;letter-spacing:0.12852px;text-indent:0px;text-transform:none;white-space:normal;word-spacing:0px">
1. Ebene: Alle Rechtecke deren linker Rand kleiner als \(x_1\) ist,
sind in linkem Teilbaum repräsentiert, alle anderen im rechten.
<p style= 
"font-weight:400;letter-spacing:0.12852px;text-indent:0px;text-transform:none;white-space:normal;word-spacing:0px">
<span style="letter-spacing: 0.12852px;">2. Ebene: Die Rechtecke,
deren rechter Rand links bzw. rechts von \(x_{21}\) liegen.</span>
<p style="letter-spacing: 0.12852px; text-indent: 0px; 
 text-transform: none; white-space: normal; word-spacing: 0px;">
<span style="letter-spacing: 0.12852px;"><b>Beispiel</b>:</span>
<p style= 
"font-weight:400;letter-spacing:0.12852px;text-indent:0px;text-transform:none;white-space:normal;word-spacing:0px">
<span style="letter-spacing: 0.12852px;">Rechtechecke beachten,
denn überlappend!</span>
<p style= 
"font-weight:400;letter-spacing:0.12852px;text-indent:0px;text-transform:none;white-space:normal;word-spacing:0px">
Beim Absteigen in Teilbäume, muss man beachten, ob es reicht, in
einen Teilbaum abzusteigen. Im Beispiel muss in beide Teilbäume
abgestiegen werden, weil \(x \geq x_{1}\) ist.
<p style= 
"font-weight:400;letter-spacing:0.12852px;text-indent:0px;text-transform:none;white-space:normal;word-spacing:0px">
<img src="paste-cae278fd2dfbfe30c7574a032259223e1857f581.jpg">
<p style= 
"font-weight:400;letter-spacing:0.12852px;text-indent:0px;text-transform:none;white-space:normal;word-spacing:0px">
Anders sieht es für \(x < x_1\) aus:
<p style= 
"font-weight:400;letter-spacing:0.12852px;text-indent:0px;text-transform:none;white-space:normal;word-spacing:0px">
<img src="paste-26e13accbfe113b5c213cee16abc73417d793b94.jpg">
<p style= 
"font-weight:400;letter-spacing:0.12852px;text-indent:0px;text-transform:none;white-space:normal;word-spacing:0px">
Hier reicht ein Absteigen in den linken Teilbaum.
