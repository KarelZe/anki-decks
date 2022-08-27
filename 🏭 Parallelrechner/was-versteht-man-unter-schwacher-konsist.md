## Note
nid: 1602347800277
model: Basic-b122e-20a86
tags: 4_3_4_4_entwurf_paralleler_programme
markdown: false

### Front
Was versteht man unter <b>schwacher Konsistenz</b>?

### Back
<ul>
  <li>Konsistenz des Speicherzugriffs muss nicht zu jeder Zeit,
  sondern nur an bestimmten, vom Programmierer gesetzten
  Synchronisationspunkten eingehalten werden.
  <li>Innerhalb kritischer Bereiche wird Inkonsistenz zugelassen.
</ul>
<div>
  <strong>Bedingungen</strong>
</div>
<ul>
  <li>Vor einem Schreibe-/Lesezugriff eines beliebigen Prozesses
  müssen alle Synchronisationspunkte erreicht sein.
  <li>Bevor eine Synchronisation bezüglich eines beliebigen
  Prozessors ausgeführt werden darf, müssen alle vorherigen Lese-/
  Schreibzugriffe ausgeführt worden sein.
</ul>
