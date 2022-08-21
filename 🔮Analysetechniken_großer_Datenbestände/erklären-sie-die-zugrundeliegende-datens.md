## Note
nid: 1633004361854
model: Basic-d7a3e
tags: 09_clustering, 09_clustering_2, checklater
markdown: false

### Front
Erklären Sie die zugrundeliegende <b>Datenstruktur</b> von
<b>OPTICS</b>.

### Back
Es wird eine Priority Queue als sg. "ControlList" verwendet.
<div>
  Kriterium ist die minimale <i>reachability distance</i> zu
  irgendeinem bereits ausgegebenem Objekt. "ControlList" enthält
  nur die Objekte, die noch nicht in Output-Liste sind.
</div>
<div>
  Es wird dann immer erst die Queue geleert, falls nicht leer,
  bevor neues Objekt zufällig aus Datenbank genommen wird.
  Abarbeitung jedes Objekts in Schleife.
</div>
<div>
  <b>Beispiel:</b>
</div>
<div>
  Wenn \(p_1\) in \(\varepsilon\)-Umgebung von dichtem Punkt \(o\)
  liegt, \(p_2\) jedoch nicht (und auch für keinen anderen bereits
  eingeordneten dichten Punkt), soll in Liste hinter \(o\) erst
  \(p_1\), dann \(p_2\) kommen.
</div>
<div><img src=
"paste-61e7f3561bb5052d0a54cca16f058bc9dfd17fbe.jpg"></div>
