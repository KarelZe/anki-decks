## Note
nid: 1632655617618
model: Basic-d7a3e
tags: 03_raeumliche_index_strukturen, checklater
markdown: false

### Front
Welche Fälle beim <b>Einfügen</b> in den R-Baum sind zu
unterscheiden?

### Back
<ul>
  <li>Punkt fällt in Zone genau eines Kind-Knotens →
  unproblematisch
  <li>Punkt fällt in Überlappung von Zonen von Kindknoten → An
  einer beliebigen (geeigneten) Stelle absteigen und einfügen
  <li>Punkt fällt in keine Zone des Kind-Knotens → betrachten um
  wie viel sich ein Bereich beim Einfügen vergrößern würde. Dann
  Bereich mit kleinsten Vergrößerung wählen.
</ul>
