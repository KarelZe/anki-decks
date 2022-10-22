# Note
```
guid: v7~[(Y98?7
notetype: Basic-b122e-20a86
```

### Tags
```
10_Cluster_Modularity
```

## Front
Wie ist die <b>Modularity</b> definiert?

## Back
\[
Q=\sum_{i=1}^{c}\left(e_{i i}-a_{i}^{2}\right)
\]

Dabei ist \(C=\left\{C_{1}, C_{2}, \ldots\right\}\) die Menge der Cluster und \(c:=|C|\) die Anzahl der Cluster.
\(e_{i j}\) und \(a_{i}\) ist definiert als:

\[
e_{i j}=\frac{\sum_{v_{x} \in C_{i}} \sum_{v_{y} \in C_{j}} m_{x y}}{\sum_{v_{x} \in V} \sum_{v_{y} \in V} m_{x y}}
\]
und
\[
a_{i}=\sum_{j=1}^{c} e_{i j}.
\]
