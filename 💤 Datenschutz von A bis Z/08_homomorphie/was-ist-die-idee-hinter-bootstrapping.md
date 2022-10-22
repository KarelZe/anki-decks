# Note
```
guid: Cj8)h,)?p0
notetype: Basic-9c783
```

### Tags
```
datenschutz::08-homomorphe-verschluesselung
ultra
```

## Front
Was ist die <b>Idee</b> hinter <b>Bootstrapping</b>?

## Back
Bootstraping ist eine Lösung für das Problem, dass ein Klartext nach mehrmaligen Operationen nicht mehr entschlüsselt werden kann. Man reduziert das Rauschen, wenn dies passiert.

Bei Bootstrapping modelliert man die Entschlüsselungsoperation als Logik-Schaltkreis. Man berechnet eine verschlüsselte Version p' vom Schlüssel p. Entschlüsselungsoperation dec p'(c) mit verschlüsseltem Schlüssel p' auf Ciphertext c erzeugt Ciphertext c' ohne Rauschen.

c darf noch nicht soviel Rauschen enthalten, dass es nicht mehr zu dekodieren ist ⚡
