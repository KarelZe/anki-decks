## Note
nid: 1613224826653
model: Basic-b122e
tags: 05_verteilter_speicher, 11_para_block_prozess
markdown: false

### Front
Wie sieht der ungefähre Ablauf für <b>synchrones,
Empfänger-initiiertes Message-Passing</b> aus?

### Back
<img src="paste-cacaf9e9353a51fb96dc93ef76eb85c9328fa0cc.jpg"><div>
</div><div>Der Sender hält eine Match Table vor.  Führt der Empfänger die RECV Funktion aus, wird eine Nachricht an die sendende Node gesendet mit "Request to Receive" ausgeführt und an den Sender gesendet. Hat der Sender bereits das SEND ausgeführt, entsteht ein match und der Nachrichtentransfer wird begonnen. Ansonsten wird mit dem SEND solange gewartet bis der zugehörige SEND vom Sender ausgeführt wurde.</div>
