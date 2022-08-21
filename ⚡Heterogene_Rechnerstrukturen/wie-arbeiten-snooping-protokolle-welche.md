## Note
nid: 1610826706815
model: Basic-b122e
tags: 04_koheraenz, 11_para_block_prozess
markdown: false

### Front
Wie arbeiten <b>Snooping-Protokolle</b>, welche zur Sicherstellung von Cache-Koheränz verwendet werden?

### Back
Jeder Cache, der eine Kopie der Daten eines Blocks des physikalischen Speichers enthält, hat ebenso eine Kopie des Zustands, in dem sich der Block befindet. D. h. durch Beobachten des Buses wird geschaut, was der Zustand der Blöcke im Cache ist.<div>
</div><div>Caches sind an einem gemeinsamen Bus angeschlossen und alle Cache-Controller "schnüffeln" am Bus mit, um zu erkennen, was über Bus transportiert wird d. h. welche Speicherzugriffe im System passieren. </div><div>
</div><div>Es wird kein zentraler Zustand festgehalten!</div>
