## Note
nid: 1593011658436
model: Basic-b122e
tags: 4_3_4_4_entwurf_paralleler_programme
markdown: false

### Front
Inkonsistenz zwischen dem Cache und dem Hauptspeicher entsteht,
wenn ein Datum / Speicherwort nur im Cache und nicht gleichzeitig
im Hauptspeicher verändert wird.
<div>
  Welche <b>zwei Protokolle</b> bestehen, um Cache-Koheränz zu
  erzielen?
</div>

### Back
<ul>
  <li><strong>Write-Update-Protokoll:</strong> Das Verändern einer
  Kopie in einem Cache müssen alle Kopien in anderen Cahces
  ebenfalls verändert werden; Aktualisierung kann auch verzögert
  (spätestens bei Zugriff) erfolgen.
  <li><strong>Write invalidate-Protokoll:</strong> Vor Verändern
  einer Kopie in einem Cache müssen alle Kopien in anderen Caches
  für ungültig erklärt werden.
</ul>
