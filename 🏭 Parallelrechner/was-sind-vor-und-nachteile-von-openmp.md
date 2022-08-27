## Note
nid: 1602352298971
model: Basic-b122e-20a86
tags: 5_2_open_mp
markdown: false

### Front
Was sind Vor- und Nachteile von OpenMP?

### Back
<ul>
  <li>(+) Portierbarer Code
  <li>(+) Einfach zu verstehen. Man muss sich nicht um den
  Nachrichtenversand wie bei MPI kümmern
  <li>(+) erlaubt ein Programmstückweise zu parallelisieren, weil
  keine großartigen Umstrukturierungen am Code gebraucht werden.
  Umsetzung geht über Derivative
  <li>(+) OpenMP unterstützt verschiedene Beschleuniger /
  Coprozessoren
  <li>(+) Führt bei Portierung von vorhandenem, sequenziellen Code
  schneller zu Ergebnissen
  <li>(-) Fehlende Möglichkeiten um ein feingranulares Mapping von
  Threads auf Prozessoren vorzunehmen.
  <li>(-) Raceconditions und Synchronizsierungsfehler sind
  schwierig aufzufinden
</ul>
