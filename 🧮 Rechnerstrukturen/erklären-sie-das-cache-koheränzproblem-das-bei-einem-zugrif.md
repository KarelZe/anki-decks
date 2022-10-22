# Note
```
guid: GepiFkP[|b
notetype: Basic-d7a3e-4ce08
```

### Tags
```
klausur
```

## Front
Erklären Sie das Cache-Koheränzproblem, das bei einem Zugriff auf gemeinsame Daten in einem Mikroprozessorsystem mit DMA-Controller und Copy-Back-Verfahren auftreten kann.

## Back
<div>
  <div>
    <ul>
      <li>Der Prozessor führt Schreibzugriff mit der Adresse aus
      dem gemeinsamen Bereich aus und aktualisiert nur den Cache;
      der DMA-Controller liest anschließend die Speicherzelle mit
      dieser Adresse.
      <li>Es folgt: der DMA-Controller liest ein veraltetes Datum
      aus dem Hauptspeicher.
    </ul>
  </div>
</div>
