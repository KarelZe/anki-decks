## Note
nid: 1612621588574
model: Basic-b122e
tags: 04_koheraenz, 11_para_block_prozess
markdown: false

### Front
Was ist die <strong>Freigabe Konsistenz</strong> (<em>release consistency</em>) (Variante der schwachen Konsistenz)?

### Back
<ul><li>Die Konsistenz des Speicherzugriffs wird nicht mehr zu allen Zeiten gewährleistet, sondern zu bestimmten, vom Programmierer in das Programm eingesetzten Synchronisationspunkten.</li><li>Einführung von kritischen Bereichen</li><ul><li>innerhalb kritischer Abschnitt wird Inkonsistenz von gemeinsamen Daten zugelassen.</li><li>Voraussetzung: Konkurrierende Lese-/Schreibzugriffe durch den kritschen Bereich unterbunden</li><li>Synchronisationspunkte sind abei die Ein-/ und Austrittspunkte der kritschen Bereich</li></ul></ul><div><img src="49374843.png">
</div>
