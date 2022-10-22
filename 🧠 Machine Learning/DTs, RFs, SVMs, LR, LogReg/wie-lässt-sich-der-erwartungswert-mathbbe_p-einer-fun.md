# Note
```
guid: Dg@#!:K~Br
notetype: Basic-d7a3e-4ce08
```

### Tags
```
ml::02_linear_classification
```

## Front
<p>Wie lässt sich der Erwartungswert \(\mathbb{E}_p\) einer
Funktion \(f(x)\) berechnen?

## Back
<p>Der Erwartungswert einer Funktion \(f(x)\) mit Berücksichtigung
der Verteilung \(p(x)\) ist gegeben durch:
<p>\(\mathbb{E}_{p}[f(x)]=\int p(x) f(x) d x\)
<p>Ein bedingter Erwartungswert ist gegeben durch:
<p>\(\mathbb{E}_{p}[f(x) \mid Y=y]=\int p(x \mid y) f(x) d x\)
<p>Kettenregel für Erwartungswerte:
<p>\(\mathbb{E}_{p}[f(x)]=\int p(y) \mathbb{E}[f(x) \mid Y=y] d y\)
