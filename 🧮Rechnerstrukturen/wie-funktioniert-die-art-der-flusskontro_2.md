## Note
nid: 1627563584018
model: Basic-d7a3e
tags: 10_verbindungsstrukturen
markdown: false

### Front
Wie funktioniert die Art der Flusskontrolle <b>wormhole switching</b>?

### Back
<div>
  <div>
    <ul>
      <li>Solange keine Ubertragungskanäle blockiert, mit
      cut-through Modus identisch Falls Kopfteil auf einen belegten
      Kanal trifft, wird er geblockt
      <li>Alle nachfolgenden Übertragungseinheiten verharren
      ebenfalls an ihrer Position, bis Blockierung aufgehoben →
      Puffer nachfolgender Kanäle für weitere Nachrichten blockiert
      <li>Es werden nur die Phits festgehalten, die die
      Wegeinformation enthalten, weshalb der Flit kleiner als ein
      Paket ist
    </ul>
  </div>
</div>
