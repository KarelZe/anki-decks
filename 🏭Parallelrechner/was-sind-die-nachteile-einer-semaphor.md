## Note
nid: 1592490088181
model: Basic-b122e
tags: 3_5_synchronisation
markdown: false

### Front
Was sind die <b>Nachteile</b> einer <b>Semaphor</b>?

### Back
<ul>
  <li>Es kann zu einem Zusammenbruch des gesamten Systems kommen,
  falls nur ein einzige Semaphoroperation falsch programmiert ist
  (z.B. das Freigeben wurde vergessen)
  <li>Lässt sich Verhindern, wenn Synchronisationswerkzeuge höherer
  Ebene, z.B. Monitore, verwendet werden.
</ul>
