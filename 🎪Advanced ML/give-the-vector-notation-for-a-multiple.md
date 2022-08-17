## Note
nid: 1619940742588
model: Basic-b122e
tags: 02_vorlesung
markdown: false

### Front
Give the <b>vector notation</b> for a <b>multiple lineare
regression</b> in model.

### Back
\(y=\beta X+\epsilon,\)
<div>
  where \(y\) is the vector consisting of \(n\) observations:
</div>
<div>
  \[y=\left[\begin{array}{c} y_{1} \\ \cdot \\ \cdot \\ \cdot \\
  y_{n} \end{array}\right]\]
</div>
<div>
  \(X\) is a matrix consisting of \(n\) observations of each of the
  \(k\) independent variables and a column of ones to account for
  the vertical intercepts \(\beta_{0}\) such that
  \[X=\left[\begin{array}{cccccc} 1 & x_{11} & . & . & . & x_{1 k}
  \\ 1 & x_{21} & . & . & . & x_{2 k} \\ . & \cdot & & & & \cdot \\
  . & \cdot & & & & \cdot \\ . & \cdot & & & & \cdot \\ 1 & x_{n 1}
  & . & . & . & x_{n k} \end{array}\right] \]
</div>
<div>
  Each observation's residual is represented in the column vector
  \(\epsilon\) and the \(k+1\) regression coefficients including
  intercept is defined as \(\beta\) :
</div>
<div>
  \[\epsilon=\left[\begin{array}{c} \epsilon_{1} \\ \cdot \\ \cdot
  \\ \cdot \\ \epsilon_{n} \end{array}\right],
  \beta=\left[\begin{array}{c} \beta_{1} \\ \cdot \\ \cdot \\
  \dot{\beta}_{k} \end{array}\right]\]
</div>
