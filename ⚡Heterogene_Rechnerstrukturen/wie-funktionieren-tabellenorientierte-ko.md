## Note
nid: 1611768964929
model: Basic-b122e
tags: 04_koheraenz
markdown: false

### Front
Wie funktionieren Tabellenorientierte-Kohärenzprotokolle?

### Back
<ul>
  <li>
    <strong>Akteure</strong>:
    <ul>
      <li>Home Knoten: Knoten (H), an dem für Speicherblock ein
      Tabelleneintrag angelegt ist.
      <li>Requester Knoten (R): Knoten, der die Anfrage sendet.
      <li>Dirty Node (D): Knoten, der die letzte modifizierte Kopie
      enthält.
      <li>Shared Node: Knoten, der eine Kopie enthält.
    </ul>
  <li>
    <strong>Beispiel:</strong> Write-Miss mit zwei Shared-Kopien
    auf anderen Knoten
    <ol>
      <li>
        <div>
          Requester sendet BusRdX Nachricht an Home Knoten
        </div>
      <li>
        <div>
          Home Knoten setzt für Eintrag Busy-Bit und sendet
          Invalidierungsnachricht an Shared Kopien (inv)
        </div>
      <li>
        <div>
          Shared Knoten bestätigen Invalidierung dem Home Knoten
          (ack)
        </div>
      <li>
        <div>
          Home sendet den Block dann an Request zurück und gibt
          Eintrag durch Zurücksetzen des Busybits frei.
        </div>
        <div><img src="Untitled.png"></div>
    </ol>
</ul>Shared Node Knoten sind die Knoten, die eine Kopie des Knotens
enthalten.
