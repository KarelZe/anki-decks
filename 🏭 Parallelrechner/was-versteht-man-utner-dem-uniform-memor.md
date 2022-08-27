## Note
nid: 1588164204338
model: Basic-b122e-20a86
tags: Einführung
markdown: false

### Front
Was versteht man utner dem Uniform-memory-access-Modell (UMA) bei speichergekoppelten Multiprozessoren?

### Back
- Alle Prozessoren greifen gleichermaßen auf einen gemeinsamen Speicher
zu, insbesondere ist die <b>Zugriffszeit </b>aller Prozessoren auf den
gemeinsamen Speicher <b>gleich</b> z. B. durch Architektur, dass alle Leiterbahnen gleich lang sind.
- Jeder Prozessor kann zusätzlich einen lokalen Cache besitzen
- Typische Beispiele: die symmetrischen Multiprozessoren (SMP)<div>
</div><div>D. h. man kann beim Programmieren davon ausgehen, dass die Zugriffszeit immer gleich lang ist, daher eher einfach zu programmieren.</div>
