## Note
nid: 1611656512919
model: Basic-d7a3e
tags: 09_clustering, 09_clustering_2, checklater
markdown: false

### Front
Was ist die <b>Komplexität</b> von <b>DBSCAN</b>?

### Back
\(\mathcal{O}(n \times \text{Laufzeit
(Epsilon-Nachbarschaftsanfrage}))\)
<div>
  Ohne räumliche Indexstruktur \(\mathcal{O}(n^2)\) wegen 1-maligen
  Durchgehen aller Objekte im Datenbestand und Prüfung der
  Nachbarschaft, dann für alle Punkte.
</div>
<div>
  Hat man räumliche Indexstruktur wie z. B. R-Baum so sind die
  Kosten für die Nachbarschaftsanfrage \(log(n)\) d. h. Kosten für
  das Absteigen im Baum.
</div>
<div>
  Die Kosten damit \(\mathcal{O}(n) log(n)\). Aber nur in den
  meisten Fällen, weil Epsilon zu groß gewählt wurde oder
  Datenbestand extrem verteilt ist, dann liefert getNeighbors alle
  Objekte zurück. Kosten sind dann linear. Hier hilft auch
  Indexstruktur dann nichts!
</div>
