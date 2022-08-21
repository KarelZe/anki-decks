## Note
nid: 1633005353616
model: Basic-d7a3e
tags: 09_clustering, 09_clustering_2, checklater
markdown: false

### Front
Erklären Sie für folgenden <b>Reachability Plot</b> den Ablauf von <b>OPTICS</b>. Gehen Sie dabei auf die ControlList ein.<div><img src="paste-3c5e54fe5f2e517e4fa2157ea806452243dbdab6.jpg">
</div><div>
</div>

### Back
<ol><li>Zu Beginn:<ol><li>DB enthält alle Objekte.</li><li>ControlList und Ausgabe - jeweils leer.</li></ol></li><li>Jetzt: Objekt 1<ul><li>Objekt 1 wird ausgegeben.</li><li>Nachbarn von Objekt 1 gemäß \(\underline{\varepsilon}\) in ControlList. Sortierkriterium: Abstand zu Objekt 1.</li></ul></li><li>Jetzt: Erstes Objekt aus ControlList entnehmen, Objekt 2.</li></ol><ul><li>Ausgabe von Objekt 2.</li><li>Nachbarn von Objekt 2 in ControlList einfügen.</li><li>Wenn bereits in ControlList, Abstand ggf. verkleinern.</li><li>Neue Objekte: Abstand zu Objekt 2 als Sortierkriterium.</li></ul><ol><li>Jetzt: Erstes Objekt aus ControlList entnehmen, Objekt 3.</li></ol><ul><li>Ausgabe von Objekt 3.</li><li>Nachbarn von Objekt 3 in ControlList einfügen.</li><li>Wenn bereits in ControlList, Abstand ggf. verkleinern.</li><li>Neue Objekte: Abstand zu Objekt 3 als Sortierkriterium.</li></ul>
