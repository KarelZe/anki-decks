# Note
```
guid: sIQv|Y;]wU
notetype: Basic-d7a3e-4ce08
```

### Tags
```
06_para_maschinenbefehl
```

## Front
Erklären und skizzieren Sie den groben Aufbau einer dynamischen Pipeline.

## Back
<img src="paste-6410c68f743dd58e8d9b2cfc34b28e985571324d.jpg">
<div>
  <b>Erklärung:</b>
</div>
<div>
  Mehrere Befehle befinden sich gleichzeitig in Ausführung.
</div>
<div>
  Befehle werden blockweise in Befehlsfenster geholt und in der
  <i>instruction decode</i> Phase decodiert.
</div>
<div>
  Bei Datenabhängigkeiten bleibt der Befehl im Befehlsfenster bis
  Ergebnis zur Verfügung steht.
</div>
<div>
  Am Ende der Berechnung stellen die unabhängigen
  Funktionseinheiten ihre Befehle bereit.
</div>
<div>
  Mit Rückordnungspuffer wird geprüft, ob Befehle von
  Sprungbedingungen abhängen.
</div>
