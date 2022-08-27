## Note
nid: 1628144321398
model: Basic-d7a3e-4ce08
tags: 07_multi_threading
markdown: false

### Front
Nennen Sie einen Vorteil und zwei Nachteile von
<b>Block-Interleaving</b> (<i>coarse grain multithreading</i>).

### Back
<div>
  <div>
    <div>
      <strong>Vorteil</strong>
    </div>
    <ul>
      <li>Die Bearbeitung eines Threads wird nicht verlangsamt, da
      beim Warten ausführbereiter Thread gestartet wird.
    </ul>
    <div>
      <strong>Nachteil</strong>
    </div>
    <ul>
      <li>Bei Thread-Wechsel leeren und Neustarten der Pipeline
      <li>Nur sinnvoll bei langen Wartezeiten
    </ul>
  </div>
</div>
