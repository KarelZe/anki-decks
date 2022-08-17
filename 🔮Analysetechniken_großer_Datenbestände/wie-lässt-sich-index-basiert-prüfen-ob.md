## Note
nid: 1632502505218
model: Basic-d7a3e
tags: 10_id_von_outliern, checklater
markdown: false

### Front
Wie lässt sich <b>Index-basiert</b> prüfen, ob ein Punkt ein
Outlier ist?

### Back
<div>
  \(k\)-Abstand := Abstand des k-nächsten Nachbarn Wenn k-Abstand
  \(< D\), dann ist Punkt kein Outlier.
</div>
<ul>
  <li>In \(DB(p, D)\)-Definition ist \(p\) der Anteil der Objekte
  “weit weg”, d. h. außerhalb der Kugel mit Radius \(D\).
  <li>Wenn Anzahl der Datenobjekte bekannt, \(k\) aus \(p\)
  berechenbar u. U.
</ul>
<div>
  Allerdings Überprüfung nur für einen Punkt, nicht “Finden
  <em>aller</em> Outlier”.
</div>
