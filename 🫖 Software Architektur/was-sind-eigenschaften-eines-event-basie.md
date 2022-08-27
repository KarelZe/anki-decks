## Note
nid: 1592125648709
model: Basic-d7a3e-4ce08
tags: 04_Architectural_Reuse, architecture, architecture_4
markdown: false

### Front
Was sind Eigenschaften eines <b>Event-basierten</b> <b>Systems</b>
<i style="">(Event-Based Architecture)</i>?

### Back
<ul>
  <li>Kommuniktion über domänen-spezifische Nachrichten z. B.
  kritscher Warenbestand.
  <li>Gibt auslösende Komponenten (senden Event) und Komponenten
  (Handler) die Event behandeln.
  <li>Komponenten sind über Eventbus gekoppelt.
  <li>Viele Instanzen sind nur durch ausgetauschte Nachrichten
  gekoppelt
    <ul>
      <li>Lose Kopplung
      <li>Dynamisches Entfernen / Hinzufügen weiterer Komponenten
      <li><em>Queing / Buffering</em> zwischen Komponenten ist
      notwendig.
    </ul>
  <li>Typischerweise Austausch von asynchronen Nachrichten
</ul>
<p><strong>Skizze:</strong>
<p><img src="paste-673b3b05e203757993c7571832f7dfb89a28f286.jpg">
