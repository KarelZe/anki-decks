## Note
nid: 1628672508696
model: Basic-d7a3e
tags: 00_introduction
markdown: false

### Front
How can one calculate the row / column averages of a matrix?

### Back
<b>row average</b>
<div>
  \[\left[\begin{array}{c} \frac{1}{m} \sum_{i=1}^{m} X_{1, i} \\
  \vdots \\ \frac{1}{m} \sum_{i=1}^{m} X_{n, i}
  \end{array}\right]=\boldsymbol{X}\left[\begin{array}{c}
  \frac{1}{m} \\ \vdots \\ \frac{1}{m}
  \end{array}\right]=\boldsymbol{X} \boldsymbol{a}, \quad \text {
  with } \boldsymbol{a}=\left[\begin{array}{c} \frac{1}{m} \\
  \vdots \\ \frac{1}{m} \end{array}\right]\]
</div>
<div>
  <b>column average</b>
</div>
<div>
  \[\left[\frac{1}{n} \sum_{i=1}^{n} X_{i, 1}, \ldots, \frac{1}{n}
  \sum_{i=1}^{n} X_{i, m}\right]=\left[\frac{1}{n}, \ldots,
  \frac{1}{n}\right] \boldsymbol{X}=\boldsymbol{b}^{T}
  \boldsymbol{X}, \text { with }
  \boldsymbol{b}=\left[\begin{array}{c} \frac{1}{n} \\ \vdots \\
  \frac{1}{n} \end{array}\right]\]
</div>
