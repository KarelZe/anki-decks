# Note
```
guid: y*9&U(j#kJ
notetype: Basic-02d89-e0e22
```

### Tags
```
05_bewertung
derivate::05_bewertung
```

## Front
Wie berechnet man <b>historische Volatilitäten</b> ausgehend des
Kursen des <b>Underlyings</b>?

## Back
Gegeben einer Zeitreihe von Kursen des Underlying \(S\left(t_{i}\right), i=0, \ldots, N\), Zeitdifferenz \(\Delta t\).

Berechne Renditen:
 \(R\left(t_{i}\right):=\ln \left(\frac{S\left(t_{i}\right)}{S\left(t_{i-1}\right)}\right)\) (zeitstetige Variante der relativen Wertpapierpreisänderungen)

Berechne Stichproben-Varianz:
\(\widehat{\sigma}^{2}:=\frac{1}{N-1} \sum_{i=1}^{N}\left(R\left(t_{i}\right)-\frac{1}{N} \sum_{j=1}^{N} R\left(t_{j}\right)\right)^{2}\)

Transformiere auf jährliche Volatilität:
\(\sqrt{\frac{{\widehat{\sigma}}^{2}}{\Delta t}}\)
