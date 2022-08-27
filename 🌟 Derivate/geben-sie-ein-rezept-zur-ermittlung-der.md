## Note
nid: 1642524325996
model: Basic-02d89-e0e22
tags: 05_bewertung, derivate::05_bewertung
markdown: false

### Front
Geben Sie ein <b>Rezept </b>zur Ermittlung der Bewertungsgleichung für <b>Aktienoptionen </b>nach <b>Black/Scholes</b> an.

### Back
Prozess der Aktie ist gegeben durch: \(d f=f_{t} \cdot d t+f_{x} \cdot d x+\frac{1}{2} f_{x x}(d x)^{2}\)

Ein Option auf die Aktie wird durch dieselbe Unsicherheitsquelle getrieben. Sei \(C(S, t)\) Preis der Option in \(t:\)
\[
\Longrightarrow d C=\left(C_{t}+C_{S} \mu S+\frac{1}{2} C_{S S} \sigma^{2} S^{2}\right) d t+C_{S} \sigma S d w
\]

Es kann damit ein lokal risikolose, selbstfinanzierendes Portfolio \(P\) mit \(\theta_{1}\) Aktien und \(\theta_{2}\) Optionen erzeugt werden.

Portfoliowert: \(P=\theta_{1} S+\theta_{2} C\)

Preisprozess des Portfolios:
\[
\begin{aligned}
d P &=\theta_{1} d S+\theta_{2} d C \\
&=\left(\theta_{1} \mu S+\theta_{2}\left(C_{t}+C_{S} \mu S+\frac{1}{2} C_{S S} \sigma^{2} S^{2}\right)\right) d t+\left(\theta_{1} \sigma S+\theta_{2} C_{S} \sigma S\right) d w
\end{aligned}
\]

Wähle \(\theta_{1}\) und \(\theta_{2}\) derart, dass \(\theta_{1}=-\theta_{2} C_{S} \Longrightarrow\)
\[
\begin{aligned}
d P &=\left(\theta_{1} \mu S+\theta_{2}\left(C_{t}+C_{S} \mu S+\frac{1}{2} C_{S S} \sigma^{2} S^{2}\right)\right) d t+\left(\theta_{1} \sigma S+\theta_{2} C_{S} \sigma S\right) d w \\
&=\left(\theta_{2} C_{t}+\theta_{2} \frac{1}{2} C_{S S} \sigma^{2} S^{2}\right) d t
\end{aligned}
\]
d.h. Portefeuille ist lokal risikolos
No-Arbitrage:
\[
d P=\operatorname{Pr} d t=\left(-\theta_{2} C_{S} S+\theta_{2} C\right) r d t
\]
Aus beiden Gleichungen oben folgt:
\[
C_{t}+C_{S} S r+\frac{1}{2} C_{S S} \sigma^{2} S^{2}=C r
\]


Spezielle Charakteristika der Derivate werden über die Randbedingungen (Anfangswertbedingungen) erfasst. Z. B. für Call: \(C(S, T)=\max (S-X, 0)\)
