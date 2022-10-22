# Note
```
guid: u[{etNa|p5
notetype: Basic-9c783
```

### Tags
```
datenschutz::02_encryption
```

## Front
Wie funktioniert <b>Blockchiffrierung</b> und welche
<b>Komponenten</b> sind dafür erforderlich?

## Back
<b>Ziel:</b> Klartexte beliebiger Länge mit kurzem Schlüssel
verschlüsseln. <b>Designprinzip:</b> Klartext wird in Blöcke fester
Länge aufgeteilt und durchläuft ein
Substitutions-Permutationsnetzwerk. In mehreren
Verschlüsselungsrunden wird:
<ol>
  <li>Rundenschlüssel auf Eingabe addiert
  <li>Ergebnis in Blöcke aufgteilt
  <li>Substitutionsbox (S1 ... S4): Einen Block durch einen anderen
  substituieren
  <li>Permutationsbox (P): Entstehende Blöcke durchmischen
</ol>In der letzten Verschlüsselungsrunde wird Rundenschlüssel
nochmals addiert. Entschlüsselung genauso nur rückwärts.
<b>Visualisierung:</b> <img src="paste-d707aace706c09312470e69e33e485c455df968e.jpg">
