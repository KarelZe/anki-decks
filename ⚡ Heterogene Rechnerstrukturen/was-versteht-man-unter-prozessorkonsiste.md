## Note
nid: 1612621194992
model: Basic-d7a3e-4ce08
tags: 04_koheraenz
markdown: false

### Front
Was versteht man unter <strong>Prozessorkonsistenz</strong>?

### Back
<ul>
  <li>Prozessorkonsistenz führt nicht mehr unbedingt zur konkreten
  Sequentialisierung der Speicherzugriffe, da Lesezugriffe (auf den
  Cache) schon erlaubt sind, bevor die ausgehenden Schreibzugriffe
  ausgeführt worden sind.
  <li>Puffern von Schreibzugriffen wird erlaubt.
  <li>Lesezugriffe können von anderen Prozessoren nicht beobachtet
  werden. Der Prozessor sieht jedoch eine Reihenfolge der
  Speicheroperationen, die nicht seiner Programmordnung entspricht.
  <li>Schreibender Prozessor muss nicht auf die Ausführung des
  Schreibzugriffs bezüglich aller Prozessoren warten, bevor er eine
  weitere Schreiboperation veranlassen kann.
</ul>
