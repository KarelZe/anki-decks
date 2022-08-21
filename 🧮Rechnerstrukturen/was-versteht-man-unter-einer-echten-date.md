## Note
nid: 1628167774693
model: Basic-d7a3e
tags: 06_para_maschinenbefehl
markdown: false

### Front
Was versteht man unter einer <b>echten Datenabhängigkeit</b>?

### Back
Ein Befehl \(j\) ist datenabhängig von einem Befehl \(i\), wobei
der Befehl \(i\) im Programm vor dem Befehl \(j\) steht, wenn
Folgendes gilt:
<div>
  <ul>
    <li>Befehl \(i\) produziert Ergebnis, das von \(j\) verwendet
    wird oder
    <li>Befehl \(j\) ist datenabhängig von Befehl \(k\) und Befehl
    \(k\) ist datenabhängig von Befehl \(i\) (Abhängigkeitskette)
  </ul>
</div>
