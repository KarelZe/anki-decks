## Note
nid: 1610819860158
model: Basic-b122e
tags: 04_koheraenz
markdown: false

### Front
Welche drei wesentliche Eigenschaften müssen gegeben sein für die Koheränz?

### Back
<ol>
  <li><b>Einhaltung der Programmordnung</b> → Lesezugriff nach
  Schreibzugriff liest geschriebenen Wert.
  <li><b>Koheränte Speichersicht</b> → Lesezugriff nach
  Schreibzugriff liest geschriebenen Wert bei ausreichendem
  zeitlichen Abstand und ohne intervenierende Schreibzugriffe.
  <li><b>Schreibzugriffserialisierung:</b> → Schreibzugriffe auf
  eine Speicherzelle werden serialisiert.
</ol>
