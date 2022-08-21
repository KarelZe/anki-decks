## Note
nid: 1608044340105
model: Basic-b122e
tags: 03_vorlesung
markdown: false

### Front
<p><span>Was sind Herausforderungen bei der Anwendungsentwicklung,
wenn ein <strong>Beschleuniger</strong> eine getrennte
Architektureinheit ist, die mit der CPU zusammenarbeitet?</span>

### Back
<ul style= 
"font-weight:400;letter-spacing:normal;text-indent:0px;text-transform:none;white-space:normal;word-spacing:0px">
  <li>Identifizierung der Programmteile, die ausgelagert werden
  sollen
  <li>Isolation von Datenstrukturen, die von beiden Programmteilen
  benötigt werden
  <li>Verwaltung der Transfers dieser Datenstrukturen zwischen
  Hauptspeicher und Beschleuniger
  <li>Synchronisation der CPU mit dem Beschleuniger
  <li>Überlappende Berechnung und Kommunikation
</ul>
