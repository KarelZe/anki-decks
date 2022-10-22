# Note
```
guid: K,=)=_Y$8)
notetype: Basic-02d89-e0e22
```

### Tags
```
05_bewertung
derivate::05_bewertung
```

## Front
Geben Sie ein <b>Rezept </b>zur Ermittlung der Bewertungsgleichung für <b>Futures </b>nach <b>Black/Scholes</b> an.

## Back
Betrachte Call mit Fälligkeit in \(T_{1}\) auf einen in \(T_{2}\) fälligen Future
Wert bei Fälligkeit: \(\max \left(0, F\left(T_{1}, T_{2}\right)-X\right)\)

Betrachte Future als Derivat auf Aktie \(\stackrel{It\hat{o}}{=} d F=\left(F_{t}+F_{s} \mu S+\frac{1}{2} F_{s s} \sigma^{2} S^{2}\right) d t+\sigma S F_{s} d w\)

Portefeuille aus \(F_{s}\) Aktien long und 1 Future short ist lokal risikolos und führt auf 
\(F_{t}+r F_{s} S+\frac{1}{2} F_{s s} \sigma^{2} S^{2}=0\)

\[
F\left(t, T_{2}\right)=S(t) e^{r\left(T_{2}-t\right)}
\]
löst die obige Bewertungsgleichung und erfült Randbedingung \(F\left(T_{2}, T_{2}\right)=S\left(T_{2}\right)\)
\(\Longrightarrow\) Dynamik des Future-Preises :
\[
\begin{aligned}
d F &=\left(-r F+e^{r\left(T_{2}-t\right)} \mu S\right) d t+\sigma S e^{r\left(T_{2}-t\right)} d w \\
&=(\mu-r) F d t+\sigma F d w
\end{aligned}
\]
Dynamik des Future-Preises entspricht Dynamik eines Aktienkurses mit stetiger Dividendenrendite \(\delta=r\)

Betrachte Kaufoption auf Future
\[
\stackrel{I t \hat{o}}{=} d C=\left(C_{t}+C_{F}(\mu-r) F+\frac{1}{2} C_{F F} \sigma^{2} F^{2}\right) d t+\sigma F C_{F} d w
\]
Portefeuille aus \(C_{F}\) Futures long und 1 Call short ist lokal risikolos und führt auf
\[
C_{t}+\frac{1}{2} \sigma^{2} F^{2} C_{F F}=r C
\]
Setze Randbedingungen:
\(C\left(T_{1}\right)=\max \left(0, F\left(T_{1}, T_{2}\right)-X\right)\)
