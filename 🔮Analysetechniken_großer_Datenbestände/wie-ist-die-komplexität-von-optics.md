## Note
nid: 1632992774142
model: Basic-d7a3e
tags: 09_clustering, 09_clustering_2, checklater
markdown: false

### Front
Wie ist die <b>Komplexität</b> von <b>OPTICS</b>?

### Back
Etwa gleich wie bei DBScan \(\mathcal{O}(n \log(n))\), sofern man eine Indexstruktur bereits hat. \(n\) ist der Aufwand, da man jedes Datenobjekt prüfen muss. \(\log(n)\) ist Aufwand für \(\epsilon\)-Nachbarschaftsanfrage.<div>
</div><div>Ohne <b>räumlichen Index</b> schlimmstenfalls \(\mathcal{O}(n^2)\).</div>
