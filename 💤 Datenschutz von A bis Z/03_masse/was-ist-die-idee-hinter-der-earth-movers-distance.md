# Note
```
guid: no}fg1[vt|
notetype: Basic-9c783
```

### Tags
```
datenschutz::03_masse
```

## Front
Was ist die <b>Idee</b> hinter der <b>Earth Mover's Distance</b>?

## Back
Earth Movers Distanz ist ein Distanz-Maß um die Ähnlichkeit
zwischen zwei Verteilungen zu bestimmen. Gegeben: Verteilung
\(P=\left\{p_1, p_2, \ldots, p_m\right\}\), Verteilung
\(Q=\left\{q_1, q_2, \ldots, q_m\right\}\) und \(\mathrm{d}_{ij}\)
: Ground Distance zwischen Element \(i\) aus \(\mathrm{P}\) und
Element \(\mathrm{j}\) aus \(\mathrm{Q}\). Finde einen Fluss
\(F=\left[f_{i j}\right]\) bei dem \(f_{i j}\) der Fluss der Masse
von Element \(i\) aus \(P\) zu Element \(j\) aus \(Q\) ist, der die
gesamte Arbeit minimiert. \(\operatorname{EMD}(P, Q)=\sum_{i=1}^m
\sum_{j=1}^m d_{i j} \mathrm{f}_{i j}\) <b>Intuition:</b> Die
Arbeit die nötig ist, um aus dem Histogramm der Äquivalenzklasse
das rechte der Gesamtverteilung zu machen, ist dann der Fluss \(f\)
und die Distanz \(d\) über alle Attributsausprägungen \(m\).
<img src="paste-8b5add0c3d0ae998bf8743fa3981b9c9c864a45d.jpg">
