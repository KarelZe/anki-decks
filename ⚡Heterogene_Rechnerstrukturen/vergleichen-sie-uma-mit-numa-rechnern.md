## Note
nid: 1615030047794
model: Basic-b122e
tags: 02_vorlesung, 04_uebung, 04_uebung_rs, 09_para_prozess_block, checklater, Eigene
markdown: false

### Front
Vergleichen Sie UMA mit NUMA Rechnern?

### Back
<b>UMA:</b><div>Alle Prozessoren greifen gleichermaßen auf einen gemeinsamen Speicher zu, insbesondere ist die <b>Zugriffszeit </b>aller Prozessoren auf den gemeinsamen Speicher <b>gleich</b> z. B. durch Architektur, dass alle Leiterbahnen gleich lang sind. Jeder Prozessor kann zusätzlich einen lokalen Cache besitzen.
</div><div>
</div><div>Typische Beispiele: die symmetrischen Multiprozessoren (SMP)
</div><div>
</div><div>
</div><div><b>NUMA: </b></div><div>Die <b>Zugriffszeiten auf Speicherzellen</b> des gemeinsamen Speichers <b>variieren je nach dem Ort</b>, an dem sich die Speicherzelle befindet.</div><div>
<div>Die Speichermodule des gemeinsamen Speichers sind physikalisch auf die Prozessoren aufgeteilt.</div><div>
</div><div>Zugriff auf entfernten Speicher über Load / Store Operationen.</div><div>
</div><div>Typische Vertreter: Distributed-Shared-Memory-Systeme.</div></div>
