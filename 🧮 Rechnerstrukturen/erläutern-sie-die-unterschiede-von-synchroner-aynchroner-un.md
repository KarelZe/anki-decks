# Note
```
guid: :{I_b:,mx
notetype: Basic-d7a3e-4ce08
```

### Tags
```
checklater
klausur
ultra
```

## Front
Erläutern Sie die Unterschiede von <b>synchroner</b>,
<b>aynchroner</b> und <b>asynchron-blockierender Kommunikation</b>
bei MPI.

## Back
<div>
  <div>
    <div>
      Blockierend heißt, dass die Durchführung der Kommunikation
      den durchführenden Prozess stoppt, bis die Kommunikation
      beendet ist. Synchronität bezieht sich auf die Durchführung
      der Kommunikation, bei der beide Prozesse zunächst
      synchronisiert werden (oder eben nicht). In letzterem Fall
      sind zusätzliche Puffer nötig, um die asynchrone Bearbeitung
      von Kommunikation zu ermöglichen. Konkret bedeutet das:
    </div>
    <ul>
      <li>Synchron: Prozess A fragt Kommunikation an, Prozess B
      liefert den Hand-Shake. Die Kommunikation findet direkt von
      Prozess zu Prozess statt und wird nach Rückbestätigung
      beendet.
      <li>Asynchron: Prozess A verwendet einen Zwischenpuffer, um
      eine Kommunikation ohne Hand-Shake durchzuführen. Auf Prozess
      B wird dabei nicht gewartet, auch eine Rückbestätigung findet
      nicht statt. Prozess B kann die Kommunikation asynchron mit
      Hilfe des Datenpuffers abschließen.
      <li>Asynchron-Blockierend: Wie bei Asynchron, nur blockiert
      Prozess A den eigenen Programmablauf, bis die Kommunikation
      für diesen Prozess abgeschlossen ist. Dadurch wird
      Kommunikation nicht überdeckt, Daten werden aber auch nicht
      während der Kommunikation versehentlich überschrieben.
    </ul>
  </div>
</div>
