# Note
```
guid: QYo|**,X=L
notetype: Basic-d7a3e-4ce08
```

### Tags
```
checklater
ml::01_linear_regression
```

## Front
<p>Wie lassen sich <b>lineare Regressionsmodelle</b> in
<b>Matrixform</b> darstellen?

## Back
<p>\[Y_{i}=\beta_{0}+\beta_{1} X_{i}+\epsilon_{i} \quad \text {
where } \quad \epsilon_{i} \sim^{i i d} N\left(0,
\sigma^{2}\right)\]
<p>\[\begin{gathered} {\left[\begin{array}{c} Y_{1} \\ Y_{2} \\
\vdots \\ Y_{n} \end{array}\right]} & =\left[\begin{array}{c}
\beta_{0}+\beta_{1} X_{1} \\ \beta_{0}+\beta_{1} X_{2} \\ \vdots \\
\beta_{0}+\beta_{1} X_{n} \end{array}\right]+\left[\begin{array}{c}
\epsilon_{1} \\ \epsilon_{2} \\ \vdots \\ \epsilon_{n}
\end{array}\right] \\ {\left[\begin{array}{c} Y_{1} \\ Y_{2} \\
\vdots \\ Y_{n} \end{array}\right]} & =\left[\begin{array}{cc} 1 &
X_{1} \\ 1 & X_{2} \\ \vdots & \vdots \\ 1 & X_{n}
\end{array}\right]\left[\begin{array}{l} \beta_{0} \\ \beta_{1}
\end{array}\right]+\left[\begin{array}{c} \epsilon_{1} \\
\epsilon_{2} \\ \vdots \\ \epsilon_{n} \end{array}\right]
\end{gathered}\]
<p>Design-Matrix
<p>\[\mathbf{X}_{n \times 2}=\left[\begin{array}{cc} 1 & X_{1} \\ 1
& X_{2} \\ \vdots & \vdots \\ 1 & X_{n} \end{array}\right]\]
<p>Vector of Parameters
<p>\[\beta_{2 \times 1}=\left[\begin{array}{l} \beta_{0} \\
\beta_{1} \end{array}\right]\]
<p>Vector of Error Terms
<p>\[\epsilon_{n \times 1}=\left[\begin{array}{c} \epsilon_{1} \\
\epsilon_{2} \\ \vdots \\ \epsilon_{n} \end{array}\right]\]
<p>Vector of Responses
<p>\[\mathbf{Y}_{n \times 1}=\left[\begin{array}{c} Y_{1} \\ Y_{2}
\\ \vdots \\ Y_{n} \end{array}\right]\]
<p>\[\begin{aligned} \mathbf{Y} &=\mathbf{X} \beta+\epsilon \\
\mathbf{Y}_{n \times 1} &=\mathbf{X}_{n \times 2} \beta_{2
\times 1}+\epsilon_{n \times 1} \end{aligned}\]
