# Note
```
guid: Q9{gY%slN3
notetype: Basic-9c783
```

### Tags
```
datenschutz::07_secure_multiparty
```

## Front
Wie funktioniert das private Skalarprodukt?

## Back
Seien \(X\) und \(Y\) zwei Spalten, die von zwei Knoten \(A\) und \(B\) gespeichert werden
\[X:=\{1,0,1,0,1,0,1,1,0,1\}\]
\[Y:=\{1,1,0,1,0,1,0,0,1,0\}\]
Skalarprodukt zweier Vektoren: \(\quad X \cdot Y=\sum_{i=1}^n x_i \cdot y_i\)
Vorgegeben: Koeffizientenmatrix \(\mathrm{C}\) mit \(\mathrm{c}_{1,1}, \ldots, \mathrm{c}_{1, n}, \ldots, \mathrm{c}_{\mathrm{n}, 1}, \ldots, \mathrm{C}_{n, n}\)
- alle Koeffizienten linear unabhängig
(zufällige Koeffizienten, die \(A\) und \(B\) gemeinsam bekannt sind)
\(A\) bestimmt eine Reihe von geheimen Zufallszahlen \(R\)
\(A\) berechnet folgenden Vektor \(X^{\prime}\) aus \(X, C\) und \(R\) und sendet inn an \(B\)
\[\begin{aligned}
&\left\langle x_1+c_{1,1} * R_1+c_{1,2} * R_2+\cdots+c_{1, n} * R_n\right\rangle \\
&\left\langle x_2+c_{2,1} * R_1+c_{2,2} * R_2+\cdots+c_{2, n} * R_n\right\rangle \\
&\vdots \\
&\left\langle x_n+c_{n, 1} * R_1+c_{n, 2} * R_2+\cdots+c_{n, n} * R_n\right\rangle
\end{aligned}\]\(B\) bestimmt eine Reihe von geheimen Zufallszahlen \(\mathrm{R}^{\prime}\).

\(B\) berechnet folgenden Vektor \(Y^{\prime}\) aus \(Y, C\) und \(R^{\prime}\) und sendet inn an \(A\)
\[\begin{aligned}
&\left\langle c_{1,1} * y_1+c_{2,1} * y_2+\cdots+c_{n, 1} * y_n+R_1^{\prime}\right\rangle \\
&\vdots \\
&\left\langle c_{1, n / r} * y_1+c_{2, n / r} * y_2+\cdots+c_{n, n / r} * y_n+R_1^{\prime}\right\rangle \\
&\left\langle c_{1,(n / r+1)} * y_1+c_{2,(n / r+1)} * y_2+\right. \\
&\left.\quad \cdots+c_{n,(n / r+1)} * y_n+R_2^{\prime}\right\rangle \\
&\vdots \\
&\left\langle c_{1,2 n / r} * y_1+c_{2,2 n / r} * y_2+\cdots+c_{n, 2 n / r} * y_n+R_2^{\prime}\right\rangle \\
&\vdots \\
&\left\langle c_{1,((r-1) n / r+1)} * y_1+c_{2,((r-1) n / r+1)} * y_2+\right. \\
&\left.\quad \cdots+c_{n,((r-1) n / r+1)} * y_n+R_r^{\prime}\right\rangle
\end{aligned}\]\(B\) sendet außerdem an \(A\)
\[\begin{aligned}
&\left\langle c_{1,1} * y_1+c_{2,1} * y_2+\cdots+c_{n, 1} * y_n\right\rangle \\
&\left\langle c_{1,2} * y_1+c_{2,2} * y_2+\cdots+c_{n, 2} * y_n\right\rangle \\
&\vdots \\
&\left\langle c_{1, n} * y_1+c_{2, n} * y_2+\cdots+c_{n, n} * y_n\right\rangle
\end{aligned}\]\(A\) kann jetzt folgendes Gleichungssystem aufstellen
\[\begin{aligned}
S=&\left(x_1+c_{1,1} * R_1+c_{1,2} * R_2+\cdots+c_{1, n} * R_n\right) * y_1 \\
&+\left(x_2+c_{2,1} * R_1+c_{2,2} * R_2+\cdots+c_{2, n} * R_n\right) * y_2 \\
& \vdots \\
&+\left(x_n+c_{n, 1} * R_1+c_{n, 2} * R_2+\cdots+c_{n, n} * R_n\right) * y_n
\end{aligned}\]
Durch Einsetzen der Gleichungen aus Schritt 3 und Termumformung lassen sich hier \(x_{i} * y_{i}\) herausziehen
- eigene Zufallszahlen \(R\) abziehen
- restliche Faktoren an \(B\) senden
- \(B\) zieht seine Zufallszahlen \(R^{\prime}\) ab und sendet Endergebnis an \(\mathrm{A}\)
