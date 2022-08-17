## Note
nid: 1581966388692
model: LaTeX
tags: Eigene
markdown: false

### Front
Was besagt das Signum? Was besagt der Fehlstand?

### Back
\textbf{Definition}<div>
</div><div>Sei $\sigma \in \operatorname{Sym}_{n}$ und $1 \leq i<j \leq n$
\begin{enumerate}</div><div><span>\item $(i, j)$ heißt ein Fehlstand von $\sigma,$ falls $\sigma(i)>\sigma(j)$</span>
</div><div>\item Ist $q(\sigma)$ die Anzahl der Fehlstände von $\sigma$, so heißt
$\operatorname{sgn}(\sigma):=(-1)^{q(\sigma)}$
das Signum von $\sigma$
</div><div>\end{enumerate}</div><div>
</div><div>% adaptiert aus Grundwissen Mathematikstudium S. 73</div><div>
</div><div>\textbf{Intuition}</div><div>
</div><div>Eine Permutation $\sigma \in \operatorname{Sym}_{n}$ der Zahlen $1,\cdots,n$ ändert deren Reihenfolge ab auf $(\sigma(1), \sigma(2), \ldots, \sigma(n))$. Ein Fehlstand von $\sigma$ ist, wenn in der Folge der Bildelemente eine größere Zahl vor einer kleineren steht, wenn also $\sigma (i)>\sigma (j)$ ist bei $i<j$.</div><div>
</div><div>Weist die Permutation $\sigma \in \operatorname{Sym}_{n}$ genau $f$ Fehlstände auf, so heißt sgn $\sigma=(-1)^{f}$ Signum der Permutation $\sigma$.
</div><div>
</div><div>% Bestehen keine Fehlstände, dann ist $\operatorname{sgn}=-1$.</div><div>
</div><div>\textbf{Beispiel}</div><div>
</div><div>So weist z. B. die Permutation $\sigma \in \operatorname{Sym}_{5}$ mit $(1,2,3,4,5) \stackrel{\sigma}{\rightarrow}(3,2,4,5,1)$ fünf Fehlstände auf, nämlich $(3,2),(3,1), (2,1), (4,1)$ und $(5,1)$, denn rechts steht $3$ vor $2$ und $1$, $2$ vor $1$, und ebenso befinden sich $4$ und $5$ vor $1$.
</div><div>
</div><div>Nach Definition im Skript wäre dann nach Definition das Tupel der Indizes anzugeben.</div>
