## Note
nid: 1638100634139
model: Basic-02d89-e0e22
tags: derivate::04_optionen
markdown: false

### Front
Welche <b>Konvexität-Beziehungen</b> im<b> Basispreis</b> gelten bei <b>Calls</b> und bei <b>Puts</b>?

### Back
\(\begin{array}{ll}C^{e, a}\left(X_{2}\right) \leq \lambda C^{e, a}\left(X_{1}\right)+(1-\lambda) C^{e, a}\left(X_{3}\right) & \text { mit } X_{1}<X_{2}<X_{3} \\ P^{e, a}\left(X_{2}\right) \leq \lambda P^{e, a}\left(X_{1}\right)+(1-\lambda) P^{e, a}\left(X_{3}\right) & \text { und } X_{2}=\lambda X_{1}+(1-\lambda) X_{3}\end{array}\)

<b>Intuition:</b>
Beweis durch "Butterfly-Spread-Strategie" (besteht aus \(C^{e}\left(X_{2}\right) \leq 0,5 C^{e}\left(X_{1}\right)+0,5 C^{e}\left(X_{3}\right)\)). Auch für amerikanische Calls gültig. Zwar hat man bei Calls short das Heft nicht in der Hand, man könnte aber bei vorzeitiger Ausübung auch die Call longs ausüben. Herleitung geometrisch möglich.
