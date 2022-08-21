## Note
nid: 1591862201289
model: LaTeX
tags: Integration_im_R_n, wichtig
markdown: false

### Front
Was besagt das \textbf{Prinzip von Cavaleri}?

### Back
% Satz 20.6 (Prinzip von Cavalieri):
<div>
  Es sei $B \subseteq \mathbb{R}^{n+1}$ messbar. Für Punkte im
  $\mathbb{R}^{n+1}$ schreiben wir $(x, z)$ mit $x \in
  \mathbb{R}^{n}$ und $z \in \mathbb{R} .$ Es seien $a, b \in
  \mathbb{R}$ so, dass $a \leq z \leq b((x, z) \in$ \[ B) \] Für $z
  \in[a, b]$ sei \[ Q(z):=\left\{x \in \mathbb{R}^{n}:(x, z) \in
  B\right\} \] Weiter sei $Q(z)$ messbar für jedes $z \in[a, b] .$
  Dann ist $z \mapsto|Q(z)|$ integrierbar über $[a, b]$ und \[
  |B|=\int_{a}^{b}|Q(z)| d z. \]
</div>
<div>
  \textbf{Beispiel:}\\
</div>
<div>
  $B:=\left\{(x, y, z) \in \mathbb{R}^{3}: x^{2}+y^{2}+z^{2} \leq
  r^{2}\right\}, r>0$ (Kugel um $(0,0,0)$ mit Radius $r$). Wähle
  $a=-r, b=r .$ Für $z \in[-r, r]$ ist \[ Q(z):=\left\{(x, y) \in
  \mathbb{R}^{2}: x^{2}+y^{2} \leq r^{2}-z^{2}\right\} \] die
  Kreisscheibe um (0,0) mit Radius $\sqrt{r^{2}-z^{2}}$. Es gilt
  $|Q(z)|=\pi\left(r^{2}-z^{2}\right) .$ Also ist \[
  |B|=\int_{-r}^{r} \pi\left(r^{2}-z^{2}\right) d z=\frac{4}{3} \pi
  r^{3}. \]
</div>
