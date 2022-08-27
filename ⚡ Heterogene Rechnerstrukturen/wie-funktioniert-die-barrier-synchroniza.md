## Note
nid: 1613216404402
model: Basic-d7a3e-4ce08
tags: 04_koheraenz
markdown: false

### Front
Wie funktioniert die <b>Barrier Synchronization</b>?

### Back
Synchronisation mehrerer Prozesse indem man:
<div>
  <ol>
    <li>Vorgabe einer Prozessgruppe/-anzahl
    <li>Barrieren-Zähler wird atomar inkrementiert für ankommende
    Prozesse.
    <li>Prozesse warten an Barriere.
    <li>Freigabe, wenn alle Prozesse angekommen sind.
  </ol>
</div>
