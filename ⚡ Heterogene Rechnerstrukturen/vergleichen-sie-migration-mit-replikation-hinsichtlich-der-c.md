# Note
```
guid: K9Sa}z)m`z
notetype: Basic-d7a3e-4ce08
```

### Tags
```
04_koheraenz
11_para_block_prozess
```

## Front
Vergleichen Sie <b>Migration</b> mit <b>Replikation</b>
hinsichtlich der <b>Cache-Koheränz</b>

## Back
<div>
  <div>
    <strong>Migration</strong>
  </div>
  <ul>
    <li>Daten können zu einem lokalen Cache migrieren und dort in
    einer transparenten Weise verwendet werden
    <li>Reduziert die Latenz für einen Zugriff auf gemeinsames
    Datum, das auf einem entfernten Speicher liegt
    <li>Reduziert auch die erforderliche Bandbreite auf den
    gemeinsamen Speicher
  </ul>
  <div>
    <strong>Replikation</strong>
  </div>
  <ul>
    <li>Gemeinsame Daten können als Kopien in lokalen Caches
    vorliegen, wenn etwa die Daten gleichzeitig gelesen werden
    <li>Reduziert die Latenz der Zugriffe und die Möglichkeit einer
    Blockierung beim Zugriff auf das gemeinsame Datum
  </ul>
</div>
