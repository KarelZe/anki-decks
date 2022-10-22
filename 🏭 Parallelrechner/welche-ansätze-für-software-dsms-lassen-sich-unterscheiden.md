# Note
```
guid: J:EjD():5v
notetype: Basic-b122e-20a86
```

### Tags
```
2_3_parallelrechner
```

## Front
Welche Ansätze für Software DSMs lassen sich unterscheiden?

## Back
<b>Seitenbasierte Ansätze
</b><ul>
<li>Illusion des gemeinsamen Adressraums durch Nutzung der virtuellen Speicherverwaltung des Betriebssystems</li>
<li>Explizite Platzierung der Daten im DSM</li>
<li>Der gemeinsame virtuelle Speicher wird in Seiten mit unterschiedlicher Granularität (z. B. 16 Byte bis zu 8 KByte) aufgeteilt</li>
<li>Völlig transparente Abwicklung des Netzwerktransfers.</li>
</ul><b>

Objektbasierte Ansätze
</b><ul>
<li>Realisierung des DSM mithilfe von speziell ausgewiesenen Speicherbereichen</li>
<li>Explizite Bekanntgabe dieser Datenstrukturen</li>
<li>Weitere Aufteilung großer Blöcke in kleinere, linear aufeinander folgende Bereiche</li>
</ul>
