## Note
nid: 1606220337692
model: Basic-d7a3e
tags: 04_entscheidungsbaeume
markdown: false

### Front
<p>Welchen Zweck haben <b>gewichtete Trainingsdatenobjekte</b>beim Aufbau von<b> Entscheidungsbäumen</b>?</p>

### Back
<div>
  <div>
    <ul>
      <li>Möchte man unterschiedlichen Trainingsdatenobjekten ein
      unterschiedliches Gewicht geben, weil z. B. das Labeling von
      Experten / Laien durchgeführt wurde, dann kann man Gewichtung
      einführen.
      <li>Gewicht wird bei Berechnung der Entropie von Splits
      berücksichtigt. d. h. Man erweitertet Entscheidungsbaum. Bei
      Berechnung der Entropie würde dann das Gewicht der
      Trainingsdaten verwendet werden.
      <li>Alternativ Überrepräsentation der Daten in
      Trainingsdatenbestand.
    </ul>
  </div>
</div>
