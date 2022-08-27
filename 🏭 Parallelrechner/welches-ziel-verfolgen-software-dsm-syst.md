## Note
nid: 1589400194201
model: Basic-b122e-20a86
tags: 2_3_parallelrechner
markdown: false

### Front
Welches Ziel verfolgen Software DSM-Systeme (Distributed Shared Memory)?

### Back
<ul>
<li>Illusion eines gemeinsamen Speichers auf Rechen-Clustern oder Multiprozessoren mit verteilten Speichern wird softwaremäßig hergestellt.
</li>
<li> Jeder Prozessor kann auf gemeinsame Daten mittels Schreib-/Leseoperationen so zugreifen, als ob ein gemeinsamer globaler Speicher zur Verfügung stünde.</li>
<li>Synchronisation über Schloß-, Semaphor- oder Bedingungsvariablen
</li>
<li>Notwendige Netzwerkkommunikation wird durch das DSM-System veranlasst (Implementierung häufig "on top of" "message passing")
</li><ul>
</ul><b>Wichtig:</b></ul><ul>Lokalität und Konsistenz der Daten  </ul><ul>
<div><div><img src="paste-ba6846c4a3d2a67d85cada82276e628b0785cb0e.jpg">
</div><div>
</div></div></ul>
