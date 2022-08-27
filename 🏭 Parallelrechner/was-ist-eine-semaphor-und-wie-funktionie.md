## Note
nid: 1592489608581
model: Basic-b122e-20a86
tags: 3_5_synchronisation
markdown: false

### Front
Was ist eine Semaphor und wie funktioniert sie?

### Back
Eine Semaphor S ist ein abstrakter Datentyp, der aus einem
<b>Semaphorzähler</b> und <b>zwei Operationen</b> besteht, die
traditionell mit P und <b>V</b> bezeichnet werden.
<div>
  Nachdem bei der Initialisierung der Semaphor dem Semaphorzähler
  nur einmal ein Wert zugewiesen werden kann, kann er nur noch mit
  den zwei primitiven, atomaren Operationen <b>P(S)</b> und
  <b>V(S)</b> manipuliert werden.
</div>
<div>
  Semaphoren lösen ein <b>Synchronisationsproblem</b> auf einer
  sehr niedrigen Ebene.
</div>
