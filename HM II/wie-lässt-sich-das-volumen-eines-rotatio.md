## Note
nid: 1598001195917
model: LaTeX
tags: Integration_im_R_n, wichtig
markdown: false

### Front
Wie lässt sich das Volumen eines Rotationskörpers berechnen?<div>
</div><div>Es sei $a<b, f \in R([a, b])$ und $f \geq 0$ auf $[a, b] .$
Der Graph von $f$ rotiere z.B. um die $x$ -Achse:
$$
B=\left\{(x, y, z) \in \mathbb{R}^{3}: y^{2}+z^{2} \leq f(x)^{2}\right\}
$$.
</div>

### Back
Für $x \in[a, b]$ ist dann $Q(x)=\left\{(y, z) \in \mathbb{R}^{2}:
y^{2}+z^{2} \leq f(x)^{2}\right\} .$ Also gilt: $|Q(x)|=\pi
f(x)^{2}$ und somit: $|B|=\pi \int_{a}^{b} f(x)^{2} d x$.
<div>
  \textbf{Beispiel:}
</div>
<div>
  Betrachte $a=0, b=4, f(x)=\sqrt{4-x}$. Dann gilt (vgl. Bsp. b)
  $)$ $$ |B|=\pi \int_{0}^{4}(4-x) d x=8 \pi. $$
</div>
