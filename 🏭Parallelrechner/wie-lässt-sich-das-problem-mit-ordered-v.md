## Note
nid: 1602347718717
model: Basic-b122e
tags: 4_3_4_4_entwurf_paralleler_programme
markdown: false

### Front
Wie lässt sich das Problem mit Ordered-Variablen lösen?

### Back
<ul>
  <li>Durch die Verwendung sogenannter Guards
  <li>D. h. für jede Ordered Variable wird eine gemeinsame (shared)
  Integer-Variable als Wächter im Programm vor dem
  Schleifeneintritt definiert.
  <li>Guard wird vor Schleifeneintritt initialisiert z. B. xguard =
  0.
  <li>Im Schleifenkörper wird vor dem ersten Zugriff auf eine zu
  schützende Ordered-Variable eine Guard-Anweisung eingeführt
  while(xguard ≠ i) continue;
  <li>Nach dem letzten Zugriff auf die Ordered-Variable wird die
  Guard-Variable inkrementiert xguard = xguard +1;
</ul>
