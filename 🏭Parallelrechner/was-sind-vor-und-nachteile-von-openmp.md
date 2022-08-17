## Note
nid: 1602352298971
model: Basic-b122e
tags: 5_2_open_mp
markdown: false

### Front
Was sind Vor- und Nachteile von OpenMP?

### Back
<ul>
<li>(+) Portierbarer Code</li>
<li>(+) Einfach zu verstehen. Man muss sich nicht um den Nachrichtenversand wie bei MPI kümmern</li>
<li>(+) erlaubt ein Programmstückweise zu parallelisieren, weil keine großartigen Umstrukturierungen am Code gebraucht werden. Umsetzung geht über Derivative</li>
<li>(+) OpenMP unterstützt verschiedene Beschleuniger / Coprozessoren</li>
<li>(+) Führt bei Portierung von vorhandenem, sequenziellen Code schneller zu Ergebnissen</li>
<li>(-) Fehlende Möglichkeiten um ein feingranulares Mapping von Threads auf Prozessoren vorzunehmen.</li>
<li>(-) Raceconditions und Synchronizsierungsfehler sind schwierig aufzufinden</li></ul>
