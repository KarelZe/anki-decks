## Note
nid: 1606220335484
model: Basic-d7a3e
tags: 04_entscheidungsbaeume
markdown: false

### Front
<p>Wie funktioniert <b>Postpruning</b> bei Entscheidungsbäumen?</p>

### Back
<p><span>
</span></p><div>
<div><ul>
<li>Entscheidungsbaum wird einmalig aufgebaut und dann zurückgeschnitten. Zurückschneiden bedeutet, dass sukzessiv ein Knoten nach dem anderen entfernt. Accuracy nimmt ab auf Trainingdaten. Fehlerrate auf Testdaten bestimmt in Hoffnung, dass verbessert. Blätter die gar ein Sinken oder konstante Fehlerrate bewirken, werden dann ausgeschlossen.</li>
<li>Kosten für Modellerstellung oft nicht arg entscheidend, da Baumaufbau einmalig erfolgt.</li></ul></div></div>
