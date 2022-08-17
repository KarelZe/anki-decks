## Note
nid: 1580142953928
model: LaTeX
tags: Logik
markdown: false

### Front
Wie ist die Verkettung von Abbildungen definiert und welche Eigenschaften hat sie?

### Back
<div>% def. 1.3.7, Obacht heißt Komposition von Funktionen!</div><div>\textbf{Definition:}\\</div><div>
</div><div>Sind $f: M \rightarrow N$ und $g: N \rightarrow O$ Funktionen, so ist ihre Komposition die Abbildung $g$ nach $f$ gegeben durch
$$
g \circ f: M \to O, \quad m \mapsto g(f(m))
$$
</div>
<div>% Zusammenfassung Abschnitt 1.3</div><div>Die Verkettung ist \textit{<span>assoziativ</span><span>}. </span><span>Seien $f: M \to N, g: N \to O$ und $h: O \to P$ Abbildungen. Dann gilt</span></div>$$
(h \circ g) \circ f=h \circ(g \circ f)
$$<div>
</div><div>\textbf{Beispiel}</div><div>
</div><div>Sei $f(x) = 2x +3$ und $g(x) = x^2 + 1$. Dann $(fg)(5)  = f(g(5)) = f(26) = 55$. <span>Hingegen ist: </span></div><div>$(gf)(5) = g(f(5)) = g(13) = 170$.</div>
