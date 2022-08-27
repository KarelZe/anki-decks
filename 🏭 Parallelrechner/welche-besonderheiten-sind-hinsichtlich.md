## Note
nid: 1602352640921
model: Basic-b122e-20a86
tags: 5_2_open_mp
markdown: false

### Front
Welche Besonderheiten sind hinsichtlich dem Gültigkeitsbereich von Variablen bei OpenMP zu beachten?

### Back
<ul>
  <li>Globale Variblen werden zwischen threads geteilt
  <li>Stapelvariablen in Unterprogrammen, die von parallel regions
  aufgerufen werden, sind privat.
  <li>Automatische Variablen innerhalb eines eines Anweisungsblocks
  sind privat.
  <li>Schleifenindizes sind standardmäßig privat
</ul>
