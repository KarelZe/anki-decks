## Note
nid: 1591514042882
model: LaTeX-deb4a
tags: Integration_im_R_n, wichtig
markdown: false

### Front
Was ist eine wichtige Folgerung aus dem \textbf{Satz von Fubini}?

### Back
% Folgerung 20.4:
<div>
  Es sei $I=\left[a_{1}, b_{1}\right] \times\left[a_{2},
  b_{2}\right] \times \ldots \times\left[a_{n}, b_{n}\right]$ und
  $f \in C(I) .$ Dann ist \[ \begin{aligned} \int_{I} f(x) d x
  &=\int_{I} f\left(x_{1}, \ldots, x_{n}\right) d\left(x_{1},
  \ldots, x_{n}\right) \\ &=\int_{a_{1}}^{b_{1}}\left(\ldots
  \int_{a_{n-1}}^{b_{n-1}}\left(\int_{a_{n}}^{b_{n}} f\left(x_{1},
  \ldots, x_{n}\right) d x_{n}\right) d x_{n-1} \ldots\right) d
  x_{1}, \end{aligned} \] wobei die Reihenfolge der Integrationen
  beliebig vertauscht werden darf.
</div>
