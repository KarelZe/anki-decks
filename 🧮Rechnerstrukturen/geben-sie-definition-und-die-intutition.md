## Note
nid: 1621150333722
model: Basic-d7a3e
tags: 04_fehlertoleranz
markdown: false

### Front
Geben Sie <b>Definition</b> und die <b>Intutition</b> für einen <b>Einzelfehlerbereich</b> an.

### Back
Wenn für ein System eine Menge von Fehlerbereichen \(F B\) definiert ist, so bezeichnen wir eine Menge von Komponenten, die genau den gleichen Fehlerbereichen angehören, als Einzelfehlerbereich. Menge der Einzelfehlerbereiche EB ist definiert:

\[\begin{array}{c}
E B=\left\{x=\left(x_{1} \cap \cdots \cap x_{q}\right) \backslash\left(x_{q+1} \cup \cdots \cup x_{f}\right): x_{1} \in F B, \ldots x_{q} \in F B\right. \\
\left.1 \leq q \leq f,\left\{x_{q+1}, \ldots, x_{f}\right\}=F B \backslash\left\{x_{1}, \ldots, x_{q}\right\} x \neq \emptyset\right\}
\end{array}\]

Für \(E B=\left\{E B_{1}, \ldots E B_{e}\right\}\) gilt \(\forall i, j \in\{1, \ldots e\}, i \neq j: E B_{i} \cap E B_{j}=\emptyset\)
und \(E B_{1} \cup \cdots \cup E B_{e}=F B_{1} \cup F B_{f}\)
