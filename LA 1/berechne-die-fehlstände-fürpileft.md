## Note
nid: 1582444461641
model: LaTeX
tags: Eigene
markdown: false

### Front
Berechne die Fehlstände für:<div>
</div><div>$$</div><div>\pi=\left(\begin{array}{lllll}{1} & {2} & {3} & {4} & {5} \\ {3} & {5} & {1} & {2} & {4}\end{array}\right) \in S_{5}</div><div>$$
</div>

### Back
<div>
  % <a href=
  "https://de.wikipedia.org/wiki/Fehlstand">https://de.wikipedia.org/wiki/Fehlstand</a>
</div>Die Menge der Fehlstände der Permutation $$
\pi=\left(\begin{array}{lllll} {1} & {2} & {3} & {4} & {5} \\ {3} &
{5} & {1} & {2} & {4} \end{array}\right) \in S_{5} $$ ist $$
\operatorname{inv}(\pi)=\{(1,3),(2,3),(1,4),(2,4),(2,5)\} $$ Man
kann diese fünf Fehlstände dadurch ermitteln, dass man in der
zweiten Zeile für jede Zahl von 1 bis $n-1$ alle Zahlen sucht, die
größer sind und links von der Zahl stehen. Im Beispiel sind dies
die Paare $(3,1),(5,1),(3,2),(5,2)$ und $(5,4)$. Die Fehlstände
sind dann die jeweils zugehörigen Zahlenpaare der ersten Zeile.
Beispielsweise ist der zu dem Paar ( $5,1$ ) zugehörige Fehlstand
das Paar ( $2,3$ ), da über der $5$ die Zahl $2$ und über der $1$
die Zahl $3$ steht.
