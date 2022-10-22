# Note
```
guid: oX;C*@9xo8
notetype: Basic-b122e-20a86
```

### Tags
```
12_relevante_objekte_empfehlen
```

## Front
Erklären Sie die Page-Rank Formel:
<div>
  \[M = (1-m)A + mS\]
</div>

## Back
<div>
  \(A\) ist dabei die Matrix, die aus der Linkstruktur abgeleitet
  wird. Sie enthält <strong>Stimmenverteilung</strong>. Die Matrix
  \(A\) enthält in einer Zeile \(k\), die Stimmanteile, die \(k\)
  von anderen Seiten erhält. Und in Spalte , die Stimmanteile, die
  \(k\) an die anderen Spalten verteilt (Folie 11 + 18). Die
  positiven Werte in Spalte \(k\) stellen die Wahrscheinlichkeit
  dar, dass ein Surfer von Seite \(k\) auf eine Seite durch
  Anklicken des Links zwischen und wechselt. (Folie 19)
</div>
<div>
  Die Matrix \(S\) ist eine Matrix mit \(s_{ij} = \frac{1}{n}\).
  Sie enthält <strong>Gleichverteilung</strong>. Die Annahme ist,
  dass ein Surfer z. B. durch Eingeben eines Links in den Browser
  auf irgendeine Seite wechselt. Die Wahrscheinlichkeit von \(k\)
  nach \(j\) zu wechseln ist damit \(\frac{1}{n}\). (Folie 19)
</div>
<div>
  Der Faktor \(m\) (typ. \(m = 0.15\)) gewichtet also dein Einfluss
  beider Verhaltensmodi (zufälliges Klicken vs. Weiternavigieren in
  Linkstruktur) des Random Surfers. (Folie 19). Behebt damit das
  Problem nicht verbundener Nodes, Dangling Nodes (und
  Spidertraps).
</div>
<div>
  \(M\) ist die Page Rank Linkmatrix.
</div>
