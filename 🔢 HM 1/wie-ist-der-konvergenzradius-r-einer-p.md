## Note
nid: 1586773022939
model: LaTeX-deb4a
tags: wichtig
markdown: false

### Front
Wie ist der Konvergenzradius $r$ einer Potenzreihe definiert?

### Back
Es sei $\sum_{n=0}^{\infty} a_{n}\left(x-x_{0}\right)^{n}$ eine
Potenzreihe. Setze $$ \rho:=\left\{\begin{array}{ll} \infty, &
\text { falls }(\sqrt[n]{\left|a_{n}\right|}) \text { unbeschränkt
} \\ \limsup _{n \rightarrow \infty} \sqrt[n]{\left|a_{n}\right|},
& \text { falls }(\sqrt[n]{\left|a_{n}\right|}) \text { beschränkt
} \end{array}\right. $$
<div>
  und $$ r:=\left\{\begin{array}{ll} 0, & \text { falls }
  \rho=\infty \\ \infty, & \text { falls } \rho=0 \\
  \frac{1}{\rho}, & \text { falls } \rho \in(0, \infty)
  \end{array}\right. $$ (kurz: $^{"} r=\frac{1}{\rho}^{"}$ ). $r$
  heißt der Konvergenzradius der Potenzreihe.
</div>
