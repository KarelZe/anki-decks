## Note
nid: 1615059036419
model: Basic-d7a3e-4ce08
tags: 05_verteilter_speicher
markdown: false

### Front
Was unterscheidet <b>synchrones </b>von <b>asynchronem Message Passing</b>?

### Back
<b>Bei snychronem Message Passing blockiert </b>der Sender solange bis die Nachricht vom Empfänger empfangen wurde. Gleichermaßen muss der Empfänger solange blockieren bis die Nachricht verfügbar ist und in eine dafür vorgesehene Datenstruktur im lokalen Adressraum kopiert wurde.<div>
</div><div>Bei <b>asynchronem Message Passing</b> wird nicht notwendigerweise gewartet bis Daten in den lokalen Adressraum kopiert wurden.</div>
