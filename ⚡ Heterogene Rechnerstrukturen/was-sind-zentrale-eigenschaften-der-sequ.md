## Note
nid: 1612615152620
model: Basic-d7a3e-4ce08
tags: 04_koheraenz, 11_para_block_prozess
markdown: false

### Front
Was sind zentrale Eigenschaften der <b>sequenziellen
Konsistenz</b>?

### Back
<ul>
  <li>Intuitiv geht Programmierer von sequentieller Konsistenz aus.
  <li>Striktestes, noch implementierbares Konsistenzmodell.
  <li>Alle Lese- und Schreibzugriffe werden in einer beliebigen
  sequentiellen Reihenfolge, die jedoch mit den jeweiligen
  Programmordnungen konform ist, am Speicher wirksam (→ keine
  Schreibpuffer).
  <li>Das Ergebnis einer Ausführung ist dasselbe wie wenn die
  Befehle aller Prozessoren in einer beliebigen aber festen
  <b>sequentiellen Reihenfolge</b> ausgeführt würden und die
  Befehle jedes einzelnen Prozessors werden in der durch das
  Programm vorgegebenen Reihenfolge ausgeführt.
</ul>
<ul>
  <li>Schreibzugriffe müssen atomar sein d. h. der jeweilige Wert
  muss überall gleichzeitig wirksam sein.
  <li>Entspricht einer überlappenden sequentiellen Ausführung
  sequentieller Operationen anstatt paralleler Ausführung.
  <li>Führt zu starken Leistungseinbußen, weil keine vorgezogenen
  Ladeoperationen, nichtblockierende Caches, Schreibpuffer bei
  RISC-Prozessoren verwendet werden können.
  <li><img src=
  "paste-5cc73bb02e23500d122ab0caf05ca0a958c5d94a.jpg">
</ul>
