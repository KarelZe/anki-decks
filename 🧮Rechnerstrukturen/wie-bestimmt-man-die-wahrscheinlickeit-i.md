## Note
nid: 1628326187843
model: Basic-d7a3e
tags: 02_uebung, 02_uebung_rs
markdown: false

### Front
Wie bestimmt man die Wahrscheinlickeit in denen ein m-von-n System eine größere Überlebenswahrscheinlichkeit als eine einzelne Komponente aufweist.

### Back
Gesucht sind Schnittpunkte von beiden Überlebenswahrscheinlichkeiten. Es muss gelten \(R(K, t)<R\left(S_{m v n}, t\right)\).<div>
</div><div>Beispiel 2-aus-3-System:</div><div>\(R\left(S_{2 v 3}, t\right)=\sum_{k=2}^{3}\left(\begin{array}{l}
3 \\
k
\end{array}\right) R(t)^{k}[1-R(t)]^{3-k}=3 * R(t)^{2}-2 * R(t)^{3}\)
</div><div>
</div><div>Gleichsetzen:</div><div>\[\begin{aligned}
R(K, t) &=R\left(S_{2 v 3}, t\right) \\
& \leftrightarrow R=3 * R^{2}-2 * R^{3} \\
& \Rightarrow R_{1}=0, R_{2}=1, R_{3}=0,5
\end{aligned}\]
</div><div>
</div><div>Einsetzen in Formel für Überlebenswahrscheinlichkeit: Hier z. B. \(R(K, t)=e^{-\lambda t}\).</div><div>
</div><div>Damit ergibt sich ein Intervall von  \(\left[t_{2}, t_{3}\right)=\left[0, \frac{\ln (2)}{\lambda}\right)\)</div>
