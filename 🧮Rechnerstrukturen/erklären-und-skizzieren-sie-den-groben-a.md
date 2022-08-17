## Note
nid: 1628165885506
model: Basic-d7a3e
tags: 06_para_maschinenbefehl
markdown: false

### Front
Erklären und skizzieren Sie den groben Aufbau einer dynamischen Pipeline.

### Back
<img src="paste-6410c68f743dd58e8d9b2cfc34b28e985571324d.jpg">
<div>
</div><div><b>Erklärung:</b></div><div>Mehrere Befehle befinden sich gleichzeitig in Ausführung.</div><div>
</div><div>Befehle werden blockweise in Befehlsfenster geholt und in der <i>instruction decode</i> Phase decodiert.</div><div>
</div><div>Bei Datenabhängigkeiten bleibt der Befehl im Befehlsfenster bis Ergebnis zur Verfügung steht. </div><div>
</div><div>Am Ende der Berechnung stellen die unabhängigen Funktionseinheiten ihre Befehle bereit. </div><div>
</div><div>Mit Rückordnungspuffer wird geprüft, ob Befehle von Sprungbedingungen abhängen. </div>
