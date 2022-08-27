## Note
nid: 1620908049617
model: Basic-d7a3e-4ce08
tags: adv_ml::09_lecture
markdown: false

### Front
Describe how one can maximize Margin \(M\) of a SVM.
<div><img src=
"paste-a172437318fd74acaea643ab4909204b3eb5908d.jpg"></div>

### Back
\[\begin{array}{l} \underset{\beta_{0}, \beta_{1}, \ldots,
\beta_{p}, \xi_{1}, \ldots, \xi_{n}}{\operatorname{maximize}} M \\
\text { subject to } \sum_{j=1}^{p} \beta_{j}^{2}=1 \\
y_{i}\left(\beta_{0}+\beta_{1} x_{i 1}+\beta_{2} x_{i
2}+\ldots+\beta_{p} x_{i p}\right) \geq M\left(1-\xi_{i}\right), \\
\quad \xi_{i} \geq 0, \quad \sum_{i=1}^{n} \xi_{i} \leq C
\end{array},\]
<div>
  where \(C\) is a nonnegative tuning parameter. The \(M\) is the
  width of the margin; we seek to make this quantity as large as
  possible.
</div>
<div>
  The \(\xi_{1}, \ldots, \xi_{N}\) are slack variables that allow
  individual observations to be on the wrong side of the margin or
  the hyperplane.
</div>
