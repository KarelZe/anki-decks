## Note
nid: 1612623856161
model: Basic-b122e
tags: 04_koheraenz
markdown: false

### Front
Welche <b>Warte-Algorithmen</b> bei
<b>Synchronisationsmechanismen</b> unterscheidet man? Erklären Sie
diese auch.

### Back
<ul>
  <li>
    <div>
      <strong>Blockierung</strong>
    </div>
    <ul>
      <li>Wartende Prozesse werden vom scheduler in den Zustand
      "wartend" versetzt
      <li>Hoher Overhead für Prozesswechsel
      <li>Prozessor kann anderweitig beschäftigt werden
    </ul>
  <li>
    <div>
      <strong>Busy Waiting</strong>
    </div>
    <ul>
      <li>Wartender Prozess testet wiederholt einen Speicherplatz
      bis er den Wert ändert
      <li>Freigebender Prozess setzt den Speicherplatz
      <li>Geringer Aufwand, weil kein Prozesswechsel, aber der
      Prozessor ist belegt
      <li>Kann hohen Speicher und Netzwerk-Verkehr bedeuten
    </ul>
</ul>
