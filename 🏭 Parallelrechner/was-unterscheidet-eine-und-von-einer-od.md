## Note
nid: 1592489400355
model: Basic-b122e-20a86
tags: 3_5_synchronisation
markdown: false

### Front
Was unterscheidet eine <b>Und-</b> von einer <b>Oder-Barriere</b>?

### Back
<b>Und-Barriere:</b> Bei der Barrieren-Synchronisation warten alle
Prozesse, welche die Barrieren-Synchronisation aufrufen, bis auch
der letzte Prozess an der Barriere angekommen ist.
<div>
  <b>Oder-Barriere / Eureka-Mechanismus:</b> Erreicht ein Prozess
  die Barriere, dann werden die anderen Prozesse abgebrochen.
  Praktisch für Suchen.
</div>
