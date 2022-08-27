## Note
nid: 1592127401020
model: Basic-d7a3e-4ce08
tags: 04_Architectural_Reuse, architecture, architecture_4
markdown: false

### Front
Was versteht Fowler unter dem Ansatz "Organized around Business Capabilities" zur Aufteilung von Microservices?

### Back
Solche Dienste erfordern eine breit angelegte Implementierung von
Software für diesen Geschäftsbereich, einschließlich
<b>Benutzerschnittstelle</b>, persistenter <b>Speicherung</b> und
jeglicher <b>externer Zusammenarbeit.</b>
<div>
  Folglich sind die Teams <b>funktionsübergreifend</b> und verfügen
  über das gesamte Spektrum der für die Entwicklung erforderlichen
  Fähigkeiten: Benutzererfahrung, Datenbank und Projektmanagement.
  Siehe nachfolgende Skizze:
  <div><img src=
  "paste-4442151da7d89625a823b6445b7d8f928742606e.jpg"></div>
  <div>
    <b>Beispiel</b>:
  </div>
  <div>
    Neuer MWST-Statz im System. Änderung würde über 3 Schichten
    auswirken. Bei Schichten-Architektur ohne Microservices müsste
    es in schwerfälliger Release-Planung berücksichtigt werden.
  </div>
</div>
