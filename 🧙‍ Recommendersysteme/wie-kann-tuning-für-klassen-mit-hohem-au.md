## Note
nid: 1591954150741
model: Basic-b122e-20a86
tags: 08_Ehrenberg
markdown: false

### Front
Wie kann <b>Tuning</b> für Klassen mit hohem Ausreißeranteil beim
<b>Ehrenberg-Recommender</b> funktionieren?

### Back
<ul>
  <li>
    <p>Evaluieren Stichprobe von <span class="math
    inline">\(n\)</span> Listen vollständig
  <li>
    <p>Tuning-Parameter sind
    <ul>
      <li>
        <p>Ausreißeranteil <span class="math inline">\(t\)</span>,
        die bei robuster Mittelwertschätzung ignoriert werden
      <li>
        <p><span class="math inline">\(\Theta\)</span>
    </ul>
  <li>
    <p>Bestimmen Fehler 1 . und 2 . Art für diese Stichprobe für
    alle <span class="math inline">\(t\)</span> und <span class= 
    "math inline">\(\theta\)</span> die uns interessieren
  <li>
    <p>Wählen beste Kombination aus und berechnen alle Empfehlungen
</ul>
