## Note
nid: 1605359133782
model: Basic-d7a3e
tags: 01_linear_regression
markdown: false

### Front
<p>Wie lässt sich die <b>Sum of squared errors (SSE)</b> in
Matrixform darstellen?

### Back
<p>
\[\operatorname{SSE}=\sum_{i}\left(y_{i}-\hat{y}_{i}\right)^{2}=\sum_{i}
e_{i}^{2}=e^{T} e=(\boldsymbol{y}-\boldsymbol{X}
\boldsymbol{w})^{T}(\boldsymbol{y}-\boldsymbol{X} \boldsymbol{w})\]
<p>Alternative <b>visuelle Darstellung</b>:
<p>\[\sum \epsilon_{i}^{2}=\left[\epsilon_{1} \epsilon_{2} \cdots
\epsilon_{n}\right]\left[\begin{array}{c} \epsilon_{1} \\
\epsilon_{2} \\ \vdots \\ \epsilon_{n}
\end{array}\right]=\epsilon^{\prime} \epsilon\]
