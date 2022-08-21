## Note
nid: 1580157124095
model: LaTeX
tags: Lineare_Abbildung
markdown: false

### Front
Was bedeutet es, dass eine Matrix in Zeilenstufenform ist?

### Back
% Definition 3.5.5 <div>\textbf{Definition:}</div><div>
</div><div>Eine Matrix $A=\left(a_{i j}\right) \in \mathbb{K}^{p \times q}$ ist in Zeilenstufenform, falls entweder $A=o$ gilt oder Elemente $r \in\{1, \ldots, p\}$ und $j_{1}, \ldots, j_{r} \in \mathbb{N}$ mit $1 \leq j_{1}<\cdots<j_{r} \leq q$ existieren, sodass für alle
$i \in\{1, \ldots, p\}$ und $j \in\{1, \ldots, q\}$ gilt:<div>\begin{enumerate}</div><div>\item $i>r \Longrightarrow a_{i j}=0$
\item $(i \in\{1, \ldots, r\}) \wedge\left(j<j_{i}\right) \Longrightarrow a_{i j}=0$
\item $i \in\{1, \ldots, r\} \Longrightarrow a_{i j_{i}} \neq 0$
<div>
</div></div><div>\end{enumerate}</div><div>
</div><div>\textbf{Visualisierung:}</div><div><div>$\left(\begin{array}{ccccccccc}{1} & {*} & {*} & {*} & {*} & {*} & {*} & {*} <span>& {*}</span><span> \\ {0} & {1} & {*} & {*} & {*} & {*} & {*} & {*} & {*} \\ {0} & {0} & {0} & {1} & {*} & {*} & {*} & {*} & {*} \\ {0} & {0} & {0} & {0} & {0} & {0} & {1} & {*} & {*} \\ {0} & {0} & {0} & {0} & {0} & {0} & {0} & {1} & {*} \\ {0} & {0} & {0} & {0} & {0} & {0} & {0} & {0} & {0} \\ {0} & {0} & {0} & {0} & {0} & {0} & {0} & {0} & {0}\end{array}\right)$</span></div><div>
</div></div></div>
