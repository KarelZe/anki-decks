## Note
nid: 1593336827757
model: Basic-d7a3e
tags: 06_getting_data, performance
markdown: false

### Front
Was ist bei der <b>Dateninterpretation</b> von <b>RUM-</b> und <b>APM-Daten</b> zu berücksichtigen?

### Back
<div>
  <ul>
    <li>RUM stellt typische Benutzungsmuster zur Verfügung z. B.
    Aufrufreihenfolge, User Think Time, durchschnittliches
    Lastverhalten, Last-Spitzen, saisonales Last-Verhalten
    <li>Probleme mit RUM sind, dass einzelne Requests
    zusammengefasst sind und die Messwerte bei RUM nur
    unstrukturiert z. B. in Log-Files vorliegen
    <li>Für das Usage Model müssen Workload Classes (repräsentative
    Aufrufsequenzen für Modellierung) gebildet werden.
    <li>Man gruppiert hierfür Nutzer mit ähnlichem Verhalten z. B.
    anhand Session-ID, IP-Adressen oder Zeitstempel unter Anwendung
    von Clustering-Algorithmen z. B. \(k\)-Means. Ähnlichkeitsmaß
    ist die Ähnlichkeit der Inputs oder Klick-Sequenzen.
  </ul>
</div>
