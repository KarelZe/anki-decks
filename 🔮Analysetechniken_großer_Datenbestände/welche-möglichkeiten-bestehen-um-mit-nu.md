## Note
nid: 1606220338038
model: Basic-d7a3e
tags: 04_entscheidungsbaeume, checklater
markdown: false

### Front
<p>Welche <b>Möglichkeiten</b> bestehen, um mit NULL-Werten bei
Entscheidungsbäumen umzugehen? (3 Stück)

### Back
<ol>
  <li>NULL als einen weiteren möglichen Wert behandeln.
  <li>Tupel beim Training nicht weiter verwenden.
  <li>Variante eines Entscheidungsbaums, die mit gewichteten
  Trainingsdatenobjekten umgehen kann, wählen. D. h.:
    <ul>
      <li>Bei Split-Findung werden NULL-Werte ignoriert
      <li>Bei Partionierung kommt Datenobjekt, das für Splitwert
      NULL hat mit Gewicht. Man schickt die Attribute mit
      Nullwerten dann den Baum hinab. Sie gehen nur mit Gewicht
      \(\frac{n_{1}}{n_{1}+n_{2}}\) bzw. nach rechts
      \(\frac{n_{2}}{n_{1}+n_{2}}\) in Blätter ein. D. h. man
      gewichtet mit der Anzahl der Objekte, die einen Wert in dem
      Attribut vorweisen im linken und rechten Teilbaum.
    </ul>
</ol>
