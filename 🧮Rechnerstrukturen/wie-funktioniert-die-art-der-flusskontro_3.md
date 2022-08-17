## Note
nid: 1627563720681
model: Basic-d7a3e
tags: 10_verbindungsstrukturen
markdown: false

### Front
Wie funktioniert die Art der Flusskontrolle <i>cut-through</i>?

### Back
<div>
  <div>
    <ul>
      <li>Kopfteil der Nachricht enthält Empfängeradresse und wird
      in jedem Schaltelement dekodiert, um Weg zu bestimmen →
      Routing OH von R Zyklen
      <li>Solange keine Blockierung, wird Paket durch
      Schaltelemente gemäß Pipeline-Verarbeitung übertragen
      <li>Kopf-Information wird bis zum letzten Phit festgehalten
      <li>Hat gesamtes Paket ein Schaltelement überquert, wird
      dieses freigegeben
      <li>Bei Blockierung wird gesamtes Paket aufgehalten
    </ul>
  </div>
</div>
