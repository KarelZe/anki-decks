## Note
nid: 1627986609540
model: Basic-d7a3e
tags: 05_uebung, 05_uebung_rs
markdown: false

### Front
Warum existiert im <b>MOESI-Protokoll</b> kein Zustandsübergang vom
Zustand S nach O?

### Back
Ein Zustandsübergang von S nach O kann es in einem
Write-Invalidate-Protokoll nicht geben. Gem. einem
Write-Invalidate-Protokoll werden bei Veränderung eines geteilten
Datums, die Daten in den entfernten Caches invalidiert und
demzufolge dem Datum der Zustand M zugewiesen.
<div>
  Der Wechsel von Zustand S in den Zustand O, müsste eine
  Aktualisierung des Datums in den entfernten Caches nach sich
  ziehen. Dies entspricht aber einem Write-Update-Protokoll.
</div>
