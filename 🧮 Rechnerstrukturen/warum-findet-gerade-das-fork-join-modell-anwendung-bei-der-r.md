# Note
```
guid: qPKg^]-px<
notetype: Basic-d7a3e-4ce08
```

### Tags
```
klausur
```

## Front
Warum findet gerade das Fork-Join-Modell Anwendung bei der Realisierung von Shared-Memory-Programmiermodellen Einsatz?

## Back
Dieses Modell ermöglicht eine einfache (halb-)automatisierte Parallelisierung, vor allem dann, wenn über gemeinsame Variablen kommuniziert werden kann. Ein Anwender muss so nur Fork- und Join-Punkte vorgeben und die Kommunikationsstruktur definieren, was wiederum über einfache Vorgaben für die verwendeten Variablen geschehen kann. OpenMP setzt exakt dieses Prinzip um.
