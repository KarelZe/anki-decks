## Note
nid: 1606220335798
model: Basic-d7a3e
tags: 04_entscheidungsbaeume, checklater
markdown: false

### Front
<p>Beim Pruning von Entscheidungsbäumen fragt man sich, ob innere Knoten durch Blätter ersetzt werden sollen.</p><p>Zur Abschätzung wird die Fehlerrate eines Knotens verwendet.</p><p>Welche <b>Möglichkeiten zur Abschätzung der Fehlerrate</b> gibt es?</p>

### Back
<div>
  <strong>Holdout-Daten</strong>
</div>
<ul>
  <li>d. h. Daten, die nicht explizit fürs Training verwendet
  werden
  <li>Ist Standard
  <li>Verkleinert Trainingsdatenbestand
</ul>
<div>
  <strong>Heuristik</strong>
</div>
<ul>
  <li>Bestimmt Fehler auf Trainingsdaten
  <li><b>Erklärung Cost-Complexity-Pruning:</b> Funktion mit no.
  der Blätter und der Fehlerrate (% der Falschklassifizierten). Man
  berechnet CC für jeden inneren Knoten als ob der Baum gepruned
  wäre. Zurückgeschnittener Baum sollte kleinere Fehlerrate haben
  sonst nicht ersetzen.
</ul>
