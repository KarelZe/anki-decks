# Note
```
guid: y.#~->K9m%
notetype: Basic-d7a3e-4ce08
```

### Tags
```
05_verteilter_speicher
11_para_block_prozess
```

## Front
Was ist der große Vorteil von <b>asynchronem Massage-Passing</b>?

## Back
Man verdeckt zeitlichen Aufwand für Kommunikation mit Berechnungen.
<div><img src="paste-d7118a78b8d442507491b736bfbe266090ff24b5.jpg"></div>
<div>
  Im Beispiel steht der Code nach dem Send nicht in Verbindung mit
  den Inhalten von A, man kann also gefahrlos mit der Ausführung
  fortfahren.
</div>
<div>
  Gleichermaßen verändert der Code Inhalte von B nicht, benötigt
  auch keine Daten von A. Man verdeckt also Latenzen mit lokalen
  Berechnungen.
</div>
