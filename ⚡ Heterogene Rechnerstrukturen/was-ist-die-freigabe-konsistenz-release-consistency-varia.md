# Note
```
guid: xyLJToH6Ab
notetype: Basic-d7a3e-4ce08
```

### Tags
```
04_koheraenz
11_para_block_prozess
```

## Front
Was ist die <strong>Freigabe Konsistenz</strong> (<em>release
consistency</em>) (Variante der schwachen Konsistenz)?

## Back
<ul>
  <li>Die Konsistenz des Speicherzugriffs wird nicht mehr zu allen
  Zeiten gewährleistet, sondern zu bestimmten, vom Programmierer in
  das Programm eingesetzten Synchronisationspunkten.
  <li>Einführung von kritischen Bereichen
  <ul>
    <li>innerhalb kritischer Abschnitt wird Inkonsistenz von
    gemeinsamen Daten zugelassen.
    <li>Voraussetzung: Konkurrierende Lese-/Schreibzugriffe durch
    den kritschen Bereich unterbunden
    <li>Synchronisationspunkte sind abei die Ein-/ und
    Austrittspunkte der kritschen Bereich
  </ul>
</ul>
<div><img src="49374843.png"></div>
