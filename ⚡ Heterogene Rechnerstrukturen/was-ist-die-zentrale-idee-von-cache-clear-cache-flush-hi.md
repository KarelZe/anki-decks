# Note
```
guid: gEp|/*cwA9
notetype: Basic-d7a3e-4ce08
```

### Tags
```
04_koheraenz
11_para_block_prozess
```

## Front
Was ist die <b>zentrale Idee</b> von <b>Cache-Clear /
Cache-Flush</b>? (hier bezogen auf Prozessor und Master)

## Back
<ul>
  <li>
    <div>
      Die Zugriffe von Prozessor und DMA-Controller werden auf den
      gemeinsamem Datenbereich von zwei unterschiedlichen Tasks
      ausgeführt. → 1. Task kann dann Löschen
    </div>
  <li>
    <div>
      <em>Write Through</em>: Cache-Clear: → Cache-Einträge werden
      auf ungültig gesetzt
    </div>
  <li>
    <div>
      <em>Copy Back</em>: Alle mit dirty gekennzeichneten Einträge
      im Cache werden in den Hauptspeicher zurückgeschrieben und
      dann Cache-Einträge auf ungültig gesetzt.
    </div>
</ul>
