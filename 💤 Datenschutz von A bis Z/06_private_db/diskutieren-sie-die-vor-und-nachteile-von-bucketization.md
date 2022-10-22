# Note
```
guid: i2;NH$E(4+
notetype: Basic-9c783
```

### Tags
```
datenschutz::06_private_db
temp
```

## Front
Diskutieren Sie die <b>Vor- und Nachteil</b>e von
<b>Bucketization</b>.

## Back
<b>Vorteil:</b>
<ul>
  <li>Kompromiss zwischen Performanz und Privatheit steuerbar
  <li>Einfach einzusetzen, kaum Änderungen am existierenden DBMS
  notwendig
</ul>
<div>
  <b>Nachteile:</b>
</div>
<div>
  <ul>
    <li>Je nach Verteilung der Attributwerte (z. B. Power-Law)
    <li>Angreifbar durch einzigartige verteilung der Indexwerte
    (1:1-Mapping) oder ordnungerhaltende Kodierung
    <li>Schlechte Performance, wenn zu viele „false positives“ in
    den Buckets oder zufällige Kodierung
  </ul>
  <div>
    <b>Visualisierung:</b>
  </div>
</div>
<div><img src="paste-066d1b23cd03e9529339886da5817ac725f660c5.jpg"></div>
