## Note
nid: 1592673191923
model: LaTeX-deb4a
tags: 21_spezielle_differntialgelichungen_1_ordnung, wichtig
markdown: false

### Front
Was ist die \textbf{Merkregel} zur Lösung von \textbf{Differentialgleichungen mit getrennten Veränderlichen}?

### Back
<div>
  \textbf{Merkregel}
</div>$y^{\prime}=f(x) g(y) \Rightarrow \frac{d y}{d x}=f(x) g(y)
\Rightarrow \frac{d y}{g(y)}=f(x) d x \Rightarrow \int \frac{d
y}{g(y)}=\int f(x) d x+c.$\\
<div>
  <div>
    \textbf{Beispiel}
  </div>
  <div>
    \[ \begin{array}{c} A W P\left\{\begin{array}{l}
    y^{\prime}(x)=e^{y(x)} \sin x \\ y(0)=0 \end{array}\right. \\
    \frac{d y}{d x}=e^{y} \sin x \Longrightarrow \frac{d
    y}{e^{y}}=\sin x d x \Longrightarrow \int \frac{d
    y}{e^{y}}=\int \sin x d x+c \\ \Rightarrow-e^{-y}=-\cos x+c
    \Longrightarrow e^{-y}=\cos x-c \Longrightarrow-y=\log (\cos
    x-c) \end{array} \] Allgemeine Lösung: \[ y(x)=-\log (\cos x-c)
    \] Lösung des Anfangswertproblems: \[ 0=y(0)=-\log (1-c)
    \Longleftrightarrow 1-c=1 \Longleftrightarrow c=0 \] Die Lösung
    des Anfangswertproblems ist also: \[ y(x)=-\log (\cos x)
    \quad\left(x \in\left(-\frac{\pi}{2},
    \frac{\pi}{2}\right)\right). \]
  </div>
</div>
