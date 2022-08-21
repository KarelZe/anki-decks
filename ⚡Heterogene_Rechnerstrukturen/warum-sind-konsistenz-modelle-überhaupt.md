## Note
nid: 1610822683380
model: Basic-b122e
tags: 04_koheraenz
markdown: false

### Front
Warum sind Konsistenz-Modelle überhaupt erforderlich?

### Back
<ul>
  <li>Ein Lesezugriff auf eine Stelle X liefert nicht immer sofort
  den Wert zurück, der von einem Schreibzugriff auf X eines anderen
  Prozesses stammt.
  <li>Folgt nämlich Schreiboperation kurz nach Leseoperation, dann
  kann nicht gesichert werden, dass Leseoperation richtigen Wert
  erhält, da Schreiboperation durch den Prozessor verzögert wird.
</ul>
