## Note
nid: 1613748620342
model: Basic-b122e
tags: 03_vorlesung, 08_heterogene_rechnerstrukturen
markdown: false

### Front
Was sind <b>Eigenschaften</b> der <b>Domain Specfic Architectures</b>?

### Back
<li>
  <strong>Maximierung des Durchsatzes pro Chip-Fläche</strong>
  <ul>
    <li>Ausnützen des Parallelismus durch feingranulare,
    datenparallele HW
    <li>SIMD
    <li>Aufwand für Optimierung liegt bei Programmierer
  </ul>
<li>
  <strong>Speichermodell, Kommunikationsmodell</strong>
  <ul>
    <li>Verwaltung des Speichers durch SW
    <li>Verwaltung durch die Hardware (Caches)
    <li>HW-Unterstützung für Interprozess-Kommunikation
    <li>Kanäle zum Speicher mit hoher Bandbreite
  </ul>
<li>
  <strong>Funktionseinheiten</strong>
  <ul>
    <li>Spezialisierte HW mit fester Funktionalität für häufige und
    reguläre Berechnungen
  </ul>
