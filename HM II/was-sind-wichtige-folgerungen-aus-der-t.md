## Note
nid: 1591514130606
model: LaTeX
tags: Integration_im_R_n, wichtig
markdown: false

### Front
Was sind wichtige Folgerungen aus der \textbf{Messbarkeit} zweier Mengen $A, B \subseteq \mathbb{R}^{n}$?

### Back
% Satz 20.5:
<div>
  Es seien $A, B \subseteq \mathbb{R}^{n}$ messbar und $\alpha,
  \beta \in \mathbb{R}$. \begin{enumerate}
</div>
<div>
  \item Ist $f \in C(B, \mathbb{R})$ beschrankt, so ist $f \in
  R(B)$ \item Es seien $f, g \in R(B)$. Dann gilt:
  \begin{enumerate}
</div>
<div>
  \item $\alpha f+\beta g, f g,|f| \in R(B)$ \[ \begin{array}{l}
  \int_{B}(\alpha f+\beta g) d x=\alpha \int_{B} f d x+\beta
  \int_{B} g d x \\ \left|\int_{B} f d x\right| \leq \int_{B}|f| d
  x \end{array} \] \item Ist $f \leq g$ auf $B$, so ist $\int_{B} f
  d x \leq \int_{B} g d x$ \item Existiert ein $\gamma>0$ mit
  $|g(x)| \geq \gamma(x \in B),$ so ist $\frac{f}{g} \in R(B)$
  <div>
    \item $\quad(i) A \cup B, A \cap B$ und $A \backslash B$ sind
    messbar. \item Aus $A \subseteq B$ folgt $|A| \leq|B|$ \item $f
    \in R(A \cup B) \Longleftrightarrow f \in R(A) \cap R(B)$. In
    diesem Fall: \[ \int_{A \cup B} f d x=\int_{A} f d x+\int_{B} f
    d x-\int_{A \cap B} f d x \] Insbesondere gilt: \[ |A \cup
    B|=|A|+|B|-|A \cap B| \] \item Es seien $f, g \in R(B)$ und $g
    \leq f$ auf $B$. Weiter sei \[ M_{f, g}:=\left\{(x, y) \in
    \mathbb{R}^{n+1}: x \in B, g(x) \leq y \leq f(x)\right\} \]
    Dann ist $M_{f, g}$ messbar $\left(i m \mathbb{R}^{n+1}\right)$
    und \[ \left|M_{f, g}\right|=\int_{B}(f-g) d x \] Ist speziell
    $g=0$ auf $B,$ so ist \[ \left|M_{f, 0}\right|=\int_{B} f d x
    \]
  </div>
</div>
<div>
  \end{enumerate}
</div>
<div>
  \end{enumerate}
</div>
