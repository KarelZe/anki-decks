## Note
nid: 1627966344439
model: Basic-d7a3e-4ce08
tags: 05_uebung, 05_uebung_rs, checklater
markdown: false

### Front
Wie unterscheiden sich direkt abgebildete (<i>direct mapped</i>),
satzassoziative (<i>set associative</i>) und vollassoziative
(<i>fully associative</i>) Caches?

### Back
<ul>
  <li>Kann ein Block überall in einem Cache auftreten, so heißt er
  direkt abgebildet. Mapping mittels (Blockadresse) mod Anzahl der
  Blöcke im Cache.
  <li>Kann ein Block überall abgelegt werden, heißt der Cache
  vollassoziativ.
  <li>Kann der Block in begrenzten Mengen abgelegt werden, so heißt
  er satzassoziativ. Die Auswahl findet per Bit-Auswahl statt:
  (Block Adresse) mod Anzahl der Mengen im Cache. Gibt es \(n\)
  Blöcke, so heißt der Cache \(n\)-fach assoziativ.
</ul>
