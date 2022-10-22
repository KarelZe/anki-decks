# Note
```
guid: x`BL;F_P2V
notetype: Basic-9c783
```

### Tags
```
datenschutz::07_secure_multiparty
ultra
```

## Front
Wie funktioniert die distributed \(k\)-secure sum?

## Back
\(k\) Nutzer: \(P_0, P_1, \ldots P_k\) mit geheimen Daten \(D_0,
D_1, \ldots D_k\) Jeder Nutzer \(p\) teilt \(D_p\) in soviele
Segmente \(D_{p, q}\) auf wie Nutzer, Summe der Blöcke bleibt
erhalten \(D_p=\sum_{q=0 . .(k-1)} D_{p, q}\). Block entspricht z.
B. Zahl. <b>Erklärung:</b>
<ol>
  <li>Teile Daten für alle Nutzer die Summanden in soviele
  Teilsummen auf wie es Nutzer gibt. Die Teilsummen sind zufällig
  und ergeben in Summe den Summanden.
  <li>Mische die Teilsummen
  <li>Initialisiere Summe mit Null.
  <li>Starte mit Nutzer 0. Dieser addiert zur Summe den Summand
  \(D_{0j}\) hinzu und sendet das Ergebnis an Nutzer 1. Letzer User
  sendet Summe + Summand an nullten User wegen \((i+1) mod k\)
  Bedingung.
  <li>Nutzer 0 addiert dann zur laufenden Summe den zweiten Summand
  den er hat hinzu \(D_{1j}\) und sendet an Nutzer 1. Man fährt mit
  Logik von (4.) und (5.) fort bis alle Summanden in Summe
  integriert sind.
  <li>Nutzer 0 verteilt finale Summe an alle User.
</ol><b>Algorithmus:</b> <img src="paste-2c41c0b7f0fdc1beac3d48a8c53894439c87d9d3.jpg">
<b>Beispiel:</b> <img src="paste-97ec5d348e7ada8a82fe2d3e012693bec057d2b2.jpg"> <img src="paste-c896234415db69996b640861ad6e0949d99ee707.jpg">
