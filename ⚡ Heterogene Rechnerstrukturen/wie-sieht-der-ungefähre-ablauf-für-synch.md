## Note
nid: 1613224790065
model: Basic-d7a3e-4ce08
tags: 05_verteilter_speicher, 11_para_block_prozess
markdown: false

### Front
Wie sieht der ungefähre Ablauf für <b>synchrones,
Sender-initiiertes Message-Passing</b> aus?

### Back
<img src="paste-4cb251f16e868d9cac54a4803b45569101ee625d.jpg">
<div>
  Im Falle von synchronem Message Passing muss der Sender, der das
  SEND ausführt, sich mit dem Empfänger synchronisieren, um
  sicherzugehen, dass dieser das zugehörige RECV erreicht hat.
</div>
<div>
  Dann kann die eigentliche Nachricht, welche die Daten enthält an
  den Empfänger gesendet werden und von dort an die spezifizierte
  Stelle im lokalen Adressraum kopiert werden.
</div>
<div>
  Der Sender sendet also eine Nachricht an den Empfänger, in der er
  nachfrägt, ob der Empfänger bereit für den Empfang ist ("Request
  to Send").
</div>
<div>
  Der Empfänge runterhält eine <b>Matching-Tabelle</b> in der die
  Stati früherer RECVs vermerkt sind.
</div>
<div>
  Wurde der RECV bereits ausgeführt, dann findet sich ein Treffer
  in der Matching-Tabelle und die sendende Node wird mti "Receiver
  Ready" darüber informiert.
</div>
<div>
  Der Sender sendet dann die Nachricht an den Empfänger und kopiert
  die Daten in einen festgelegten Bereich im lokalen Adressraum.
</div>
<div>
  Wurde das RECV noch nicht vom Empfänger ausgeführt, wird solange
  gewartet, bis die RECV function ausgeführt wurde.
</div>
