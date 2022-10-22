# Note
```
guid: t{}&q9qG[[
notetype: Basic-b122e-20a86
```

### Tags
```
2_parallelrechner
```

## Front
Welche Probleme treten bei der Replikation in Konsistenzmodellen auf?

## Back
Verschiedene Kopien müssen konsistent gehalten werden.<div>
</div><div>Zahlreiche Lösungen zur Konsistenzhaltung existieren, jedoch beeinflussen sie die Leistung des Gesamtsystems negativ.
</div><div>
</div><div><b>Dilemma: </b>bessere Skalierbarkeit und damit bessere Leistung soll
erreicht werden, aber die dazu notwendigen Mechanismen
verschlechtern die Performance.
</div><div>
</div><div><b>Einzige Lösung: </b>keine strikte Konsistenz, d.h. Replikate müssen nicht zu jeder Zeit absolut identisch sein; sie können es tatsächlich auch nicht sein.
</div>
