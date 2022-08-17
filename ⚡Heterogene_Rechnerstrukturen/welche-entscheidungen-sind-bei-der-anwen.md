## Note
nid: 1613747712438
model: Basic-b122e
tags: 08_heterogene_rechnerstrukturen
markdown: false

### Front
Welche <b>Entscheidungen</b> sind bei der Anwendungsentwicklung von
Programmen mit <b>Beschleuniger-Unterstützung</b> zu beachten?

### Back
<div>
<div><ul>
<li>Identifizierung des Programmteils, der auf Beschleuniger ausgelagert werden?</li>
<li>Isolation der Datenstrukturen, die von dem Programmteil benötigt werden.</li>
<li>Verwaltung
 der Transfers der Datenstrukturen zwischen Speicher und Beschleuniger 
(wichtig, wenn Beschleuniger eignen Adressraum hat)</li>
<li>Synchronisation von CPU und Beschleuniger</li>
<li>Überlappung von Berechnungen und Kommunikation</li>
</ul>
</div></div>
