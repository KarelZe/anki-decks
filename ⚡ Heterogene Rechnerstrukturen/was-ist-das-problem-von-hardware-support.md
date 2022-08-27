## Note
nid: 1613226356465
model: Basic-d7a3e-4ce08
tags: 05_verteilter_speicher, 11_para_block_prozess
markdown: false

### Front
Was ist das Problem von <b>Hardware-Support</b> durch <b>DMA</b>
bei <b>Message Passing</b>?

### Back
<div>
  DMA-Unterstützung ist sehr <b>aufwändig</b>. Siehe:
</div>
<ol>
  <li>Es kommen Daten an.
  <li>Unterbrechung in der DMA-Prozess angestoßen wird, um Daten
  vom Systembereich von der Netzwerkschnittstelle in den
  Systembereich zu kopieren (1) (2)
  <li>Prozessor wird informiert, dass Daten im Systembereich sind.
  <li>Erneute Unterbrechung, dass DMA die Daten aus Systembereich
  in Benutzerbereich kopieren kann. (3) (4)
</ol>
<div><img src=
"paste-18aa6f54a38b5989d4adc437f4fc91cfc9531973.jpg"></div>
<div>
  Die DMA (direct memory access) engine kann die Daten von der
  Netzwerkschnittstelle zum Benutzerbereich kopieren (blaue, dicke
  Pfeile). Gleichermaßen kann sie auch Daten zur
  Netzwerkschnittstelle kopieren.
</div>
<div>
  Eingehende Nachrichten werden mit Routinen auf OS Ebene
  verarbeitet. Die DMA ist ausgelegt die ankommenden Nachrichten in
  den Systembereich zu spulen.
</div>
