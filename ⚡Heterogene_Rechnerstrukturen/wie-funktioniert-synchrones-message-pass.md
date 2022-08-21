## Note
nid: 1613223150917
model: Basic-b122e
tags: 05_verteilter_speicher
markdown: false

### Front
Wie funktioniert <b>synchrones Message-Passing</b>?

### Back
<img src="paste-f8766aaeab35b33ea8c54f64215f9f935fbc9274.jpg">
<div>
  C = 11
</div>
<div>
  Ein übereinstimmendes Paar aus SEND und RECV Primitiven setzt
  einen Kommunikationspfad auf, sodass Daten aus einer Stelle im
  lokalen Adressraum des Senders in den lokalen Adressraum des
  Empfängers kopiert werden können.
</div>
<div>
  Im obigen Beispiel garantiert ein SEND/RECV Protokoll, dass der
  Inhalt von A, so ist ist, wie zum Zeitpunkt an dem das SEND
  Primitiv ausgeführt wurde, wird es korrekt in den Speicher von B
  kopiert ehe P2 den Befehl ausführt, der den Inhalt von B
  verändert.
</div>
