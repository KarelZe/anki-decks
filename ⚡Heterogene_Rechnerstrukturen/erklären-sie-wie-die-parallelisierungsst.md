## Note
nid: 1612889578119
model: Basic-b122e
tags: 06_programmiermodelle
markdown: false

### Front
Erklären Sie wie die Parallelisierungsstrategie <b>Pipeline (Producer / Consumer)</b> funktioniert.

### Back
<ul><li><div>Nachrichten werden von einem Prozess / Thread zum nächsten geschickt.</div></li><li><div><strong>Beispiel</strong>: Bildverarbeitung, z. B. zuerst Weißabgleich, dann Filter, dann Reduzierung</div></li></ul><div><b>Visualisierung der aufeinanderfolgenden Threads:</b></div><div>
</div><img src="28334820.png"><div>Ist T1 mit Abarbeitung fertig, kann er sich neuem Task widmen.</div>
