## Note
nid: 1589401490422
model: Basic-b122e
tags: 2_3_parallelrechner
markdown: false

### Front
Welche Ansätze für Software DSMs lassen sich unterscheiden?

### Back
<b>Seitenbasierte Ansätze</b>
<ul>
  <li>Illusion des gemeinsamen Adressraums durch Nutzung der
  virtuellen Speicherverwaltung des Betriebssystems
  <li>Explizite Platzierung der Daten im DSM
  <li>Der gemeinsame virtuelle Speicher wird in Seiten mit
  unterschiedlicher Granularität (z. B. 16 Byte bis zu 8 KByte)
  aufgeteilt
  <li>Völlig transparente Abwicklung des Netzwerktransfers.
</ul><b>Objektbasierte Ansätze</b>
<ul>
  <li>Realisierung des DSM mithilfe von speziell ausgewiesenen
  Speicherbereichen
  <li>Explizite Bekanntgabe dieser Datenstrukturen
  <li>Weitere Aufteilung großer Blöcke in kleinere, linear
  aufeinander folgende Bereiche
</ul>
