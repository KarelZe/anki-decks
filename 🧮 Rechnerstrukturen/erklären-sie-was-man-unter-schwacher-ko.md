## Note
nid: 1616791691971
model: Basic-d7a3e-4ce08
tags: 11_para_block_prozess
markdown: false

### Front
Erklären Sie, was man unter <b>schwacher Konsistenz</b> versteht?

### Back
<div>
  <ul>
    <li>Konsistenz des Speicherzugriffs muss nicht zu jeder Zeit,
    sondern nur an bestimmten, vom Programmierer gesetzten
    Synchronisationspunkten eingehalten werden.
    <li>Innerhalb kritischer Bereiche wird Inkonsistenz zugelassen.
    <li>Konkurrierende Zugriffe auf gemeinsame Daten werden durch
    geeignete Synchronsationen z. B. Locks geschützt.
  </ul>
</div>
