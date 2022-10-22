# Note
```
guid: zc!JY.Vmli
notetype: LaTeX-deb4a
```

### Tags
```
differentialrechnung_im_R_n
wichtig
```

## Front
Was besagt der Umkehrsatz? Vollziehen Sie das gezeigte Beispiel nach.

## Back
% Satz 19.6 (Der Umkehrsatz (ohne Beweis)):
<div>
  Es sei $D \subseteq \mathbb{R}^{n}$ offen, $f \in C^{1}\left(D,
  \mathbb{R}^{n}\right)$ und $x_{0} \in D .$ Ist det
  $f^{\prime}\left(x_{0}\right) \neq 0,$ so existiert ein
  $\delta>0$ mit: \begin{enumerate}
</div>
<div>
  \item $U_{\delta}\left(x_{0}\right) \subseteq D$ und
  $f\left(U_{\delta}\left(x_{0}\right)\right)$ ist offen, \item $f$
  ist auf $U_{\delta}\left(x_{0}\right)$ injektiv, \item $f^{-1}:
  f\left(U_{\delta}\left(x_{0}\right)\right) \rightarrow
  U_{\delta}\left(x_{0}\right)$ ist in
  $C^{1}\left(f\left(U_{\delta}\left(x_{0}\right)\right),
  \mathbb{R}^{n}\right)$ \[ \operatorname{det} f^{\prime}(x) \neq 0
  \quad\left(x \in U_{\delta}\left(x_{0}\right)\right) \] und \[
  \left(f^{-1}\right)^{\prime}(y)=\left(f^{\prime}\left(f^{-1}(y)\right)\right)^{-1}
  \quad\left(y \in
  f\left(U_{\delta}\left(x_{0}\right)\right)\right). \]
</div>
<div>
  \end{enumerate}
</div>
<div>
  \textbf{Beispiel:}
</div>
<div>
  $D=\mathbb{R}^{2}, f(x, y)=\left(e^{x} \cos y, e^{x} \sin
  y\right)$ $f^{\prime}(x, y)=\left(\begin{array}{cc}e^{x} \cos y &
  -e^{x} \sin y \\ e^{x} \sin y & e^{x} \cos y\end{array}\right)$,
</div>
<div>
  \[ \operatorname{det} f^{\prime}(x, y)=e^{2 x} \cos ^{2} y+e^{2
  x} \sin ^{2} y=e^{2 x} \neq 0 \quad\left((x, y) \in
  \mathbb{R}^{2}\right). \] Es sei $\left(x_{0}, y_{0}\right) \in
  \mathbb{R}^{2} .$ Nach 19.6 gilt: Es gibt ein $\delta>0$ mit:
  $f$ ist auf $U_{\delta}\left(\left(x_{0}, y_{0}\right)\right)$
  injektiv. Aber: $f$ ist auf $\mathbb{R}^{2}$ nicht injektiv: \[
  f(x, y)=f(x, y+2 k \pi) \quad(k \in \mathbb{Z}). \] Betrachte
  speziell $\left(x_{0}, y_{0}\right):=\left(0,
  \frac{\pi}{2}\right) .$ Es gilt $f\left(0,
  \frac{\pi}{2}\right)=(0,1),$ also $f^{-1}(0,1)=\left(0,
  \frac{\pi}{2}\right)$ und \[
  \left(f^{-1}\right)^{\prime}(0,1)=\left(f^{\prime}\left(0,
  \frac{\pi}{2}\right)\right)^{-1}=\left(\begin{array}{cc} 0 & -1
  \\ 1 & 0 \end{array}\right)^{-1}=\left(\begin{array}{cc} 0 & 1 \\
  -1 & 0 \end{array}\right). \]
</div>
