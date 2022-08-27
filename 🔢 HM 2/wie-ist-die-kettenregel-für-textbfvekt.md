## Note
nid: 1590312546743
model: LaTeX-deb4a
tags: vektorwertige_funktionen
markdown: false

### Front
Wie ist die Kettenregel für \textbf{vektorwertige Funktionen} im $\mathbb{R}^n$ definiert?

### Back
% Satz 19.3 (Die Kettenregel (ohne Beweis)):
<div>
  Es sei $f: D \rightarrow \mathbb{R}^{m}$ in $x_{0} \in D$
  differenzierbar es sei $\widetilde{D} \subseteq \mathbb{R}^{m}$
  offen, $f(D) \subseteq \widetilde{D}$ und $g: \widetilde{D}
  \rightarrow \mathbb{R}^{p}$ sei differenzierbar in
  $y_{0}:=f\left(x_{0}\right)$. Dann ist \[ \phi:=g \circ f: D
  \rightarrow \mathbb{R}^{p} \] in $x_{0}$ differenzierbar und \[
  \phi^{\prime}\left(x_{0}\right)=(g \circ
  f)^{\prime}\left(x_{0}\right)=\underbrace{g^{\prime}\left(f\left(x_{0}\right)\right)
  \cdot f^{\prime}\left(x_{0}\right)}_{\text {Matritzenprodukt}}.
  \]
</div>
