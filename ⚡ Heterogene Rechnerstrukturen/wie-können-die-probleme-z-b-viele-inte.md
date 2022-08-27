## Note
nid: 1613226653743
model: Basic-d7a3e-4ce08
tags: 05_verteilter_speicher, 11_para_block_prozess
markdown: false

### Front
Wie können die Probleme z. B. viele Interrupts von DMA bei hardware-unterstütztem Message-Passing beseitigt werden?

### Back
Man integriert einen <b>seperaten Prozessor</b> in der
<b>Netzwerkschnittstelle</b>, der <b>Netzwerkprotokolle</b>
integriert. Er implementiert dann abstraktere Funktionen wie das
matching von Nachrichten, das Formen von Paketen oder das Versenden
von Bestätigungen.
<div><img src=
"paste-4b1d43e897780768c4ac2306f17e40beea96b828.jpg"></div>
