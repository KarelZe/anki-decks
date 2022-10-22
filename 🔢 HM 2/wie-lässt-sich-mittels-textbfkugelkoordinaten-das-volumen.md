# Note
```
guid: ejhf~-OX}*
notetype: LaTeX-deb4a
```

### Tags
```
Integration_im_R_n
wichtig
```

## Front
Wie lässt sich mittels \textbf{Kugelkoordinaten} das Volumen von Körpern berechnen?

## Back
% 20.10 Kugelkoordinaten $(n=3):$
<div>
  Für $\varphi=[0,2 \pi], \vartheta \in\left[-\frac{\pi}{2},
  \frac{\pi}{2}\right]$ $$ \begin{array}{c} r=\|(x, y,
  z)\|=\sqrt{x^{2}+y^{2}+z^{2}}, x=\tau \cos \varphi \cos
  \vartheta, y=r \sin \varphi \cos \vartheta, z=r \sin \vartheta \\
  g(r, \varphi, \vartheta):=(r \cos \varphi \cos \vartheta, r \sin
  \varphi \cos \vartheta, r \sin \vartheta) \end{array} $$
</div>
<div>
  $$ \left|\operatorname{det} g^{\prime}(r, \varphi,
  \vartheta)\right|=r^{2} \cos \vartheta $$ Sind $A, B \subseteq
  \mathbb{R}^{S}$ wie in 20.6 (also $A=g(B)$ ), so gilt für $f \in
  C(A, \mathbb{R})$ : $$ \int_{A} f(x, y, z) d(x, y, z)=\int_{B}
  f(g(r, \varphi, \vartheta)) \cdot r^{2} \cos \vartheta d(r,
  \varphi, \vartheta) $$
</div>
<div>
  \textbf{Beispiel}\\
</div>
<div>
  Es sei $$ \begin{array}{c} A=\left\{(x, y, z) \in \mathbb{R}^{3}:
  x, y, z \geq 0, x^{2}+y^{2}+z^{2} \leq 1\right\} \\ \text { Für }
  B=\underbrace{\left[\begin{array}{l} 0,1 \end{array}\right]}_{r}
  \times \underbrace{\left[0, \frac{\pi}{2}\right]}_{\varphi}
  \times \underbrace{\left[0, \frac{\pi}{2}\right]}_{\vartheta}
  \text { ist } g(B)=A \end{array} $$ Also gilt: $$ \begin{aligned}
  \int_{A} x \sqrt{x^{2}+y^{2}+z^{2}} d(x, y, z) &=\int_{B}(r
  \cos \varphi \cos \vartheta) r r^{2} \cos \vartheta d(r, \varphi,
  \vartheta) \\ &=\int_{B} r^{4} \cos ^{2} \vartheta \cos
  \varphi d(r, \varphi, \vartheta) \\
  &=\int_{0}^{1}\left(\int_{0}^{\frac{\pi}{2}}\left(\int_{0}^{\frac{\pi}{2}}
  r^{4} \cos ^{2} \vartheta \cos \varphi d \varphi\right) d
  \vartheta\right) d r \\
  &=\int_{0}^{1}\left(\int_{0}^{\frac{\pi}{2}} r^{4} \cos ^{2}
  \vartheta d \vartheta\right) d r \\ &=\frac{1}{5}
  \int_{0}^{\frac{\pi}{2}} \cos ^{2} \vartheta d
  \vartheta=\frac{\pi}{20} \end{aligned} $$
</div>
