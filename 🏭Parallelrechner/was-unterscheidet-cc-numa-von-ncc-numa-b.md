## Note
nid: 1589400851804
model: Basic-b122e
tags: 2_3_parallelrechner
markdown: false

### Front
Was unterscheidet <b>CC NUMA</b> von <b>NCC-NUMA</b> bei
DSM-Systemen?

### Back
<div>
  In der Regel werden zusätzliche Cache Speicher (prozessorinterne
  Primär Cache Speicher und optionale Sekundär Cache Speicher)
  verwendet.
</div>Diese können die Cache Kohärenz über sämtliche Cache Speicher
des gesamten Systems sichern (<b>CC NUMA</b> und <b>COMA</b>), oder
sie puffern Cache Blöcke nur im Falle eines prozessorlokalen
Speicherzugriffs (<b>NCC NUMA</b>).
