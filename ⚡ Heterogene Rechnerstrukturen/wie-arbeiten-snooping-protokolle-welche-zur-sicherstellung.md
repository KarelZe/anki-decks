# Note
```
guid: dLj_{n+rbl
notetype: Basic-d7a3e-4ce08
```

### Tags
```
04_koheraenz
11_para_block_prozess
```

## Front
Wie arbeiten <b>Snooping-Protokolle</b>, welche zur Sicherstellung
von Cache-Koheränz verwendet werden?

## Back
Jeder Cache, der eine Kopie der Daten eines Blocks des
physikalischen Speichers enthält, hat ebenso eine Kopie des
Zustands, in dem sich der Block befindet. D. h. durch Beobachten
des Buses wird geschaut, was der Zustand der Blöcke im Cache ist.
<div>
  Caches sind an einem gemeinsamen Bus angeschlossen und alle
  Cache-Controller "schnüffeln" am Bus mit, um zu erkennen, was
  über Bus transportiert wird d. h. welche Speicherzugriffe im
  System passieren.
</div>
<div>
  Es wird kein zentraler Zustand festgehalten!
</div>
