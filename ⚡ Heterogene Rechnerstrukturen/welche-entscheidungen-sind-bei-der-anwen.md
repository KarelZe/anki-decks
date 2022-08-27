## Note
nid: 1613747712438
model: Basic-d7a3e-4ce08
tags: 08_heterogene_rechnerstrukturen
markdown: false

### Front
Welche <b>Entscheidungen</b> sind bei der Anwendungsentwicklung von
Programmen mit <b>Beschleuniger-Unterstützung</b> zu beachten?

### Back
<div>
  <div>
    <ul>
      <li>Identifizierung des Programmteils, der auf Beschleuniger
      ausgelagert werden?
      <li>Isolation der Datenstrukturen, die von dem Programmteil
      benötigt werden.
      <li>Verwaltung der Transfers der Datenstrukturen zwischen
      Speicher und Beschleuniger (wichtig, wenn Beschleuniger
      eignen Adressraum hat)
      <li>Synchronisation von CPU und Beschleuniger
      <li>Überlappung von Berechnungen und Kommunikation
    </ul>
  </div>
</div>
