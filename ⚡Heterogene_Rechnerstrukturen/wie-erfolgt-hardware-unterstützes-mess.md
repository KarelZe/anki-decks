## Note
nid: 1613226470740
model: Basic-b122e
tags: 05_verteilter_speicher
markdown: false

### Front
Wie erfolgt (hardware-unterstützes) <b>Message-Passing</b> mit
<b>DMA</b>?

### Back
Wir haben Controller, der die Datenübertragung zwischen Netzwerkschnittstelle und Knoten entsprechend durchführt.

Erhalt Nachricht in In-Puffer der Netzwerk-Schnittstelle. Daten sind im Systembereich abgebildet.

Von Systembereich müssen Daten in Benutzerbereich kopiert werden. Unterstützt durch DMA.
