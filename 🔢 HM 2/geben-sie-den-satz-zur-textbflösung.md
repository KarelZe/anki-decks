## Note
nid: 1593855838779
model: LaTeX-deb4a
tags: 22_lineare_systeme_mit_konstanten_koeffizienten, wichtig
markdown: false

### Front
Geben Sie den Satz zur \textbf{Lösung} \textbf{inhomogener, linearer Differentialgelichungssysteme}

### Back
% Satz 22.2 (ohne Beweis):
<div>
  Für alle $x \in \mathbb{R}$ gilt: det $Y(x) \neq 0$ Für eine
  spezielle Lösung $y_{p}: I \rightarrow \mathbb{R}^{n}$ von (1)
  gehe wie folgt vor: \[ \text { Ansatz: } y_{p}(x)=Y(x) c(x) \]
  mit einer noch unbekannten Funktion $c: I \rightarrow
  \mathbb{R}^{n}$. Dann gilt:
</div>
<div>
  $y_{p}$ ist eine Lösung von (1) auf $I \Longleftrightarrow
  c^{\prime}(x)=(Y(x))^{-1} b(x)(x \in I)$
</div>
<div>
  Wähle eine Stammfunktion \[ c(x)=\int(Y(x))^{-1} b(x) d x \] und
  erhalte damit $y_{p}$.
</div>
