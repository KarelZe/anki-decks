# Note
```
guid: cK/}i]7[5b
notetype: Basic-d7a3e-4ce08
```

### Tags
```
ml::00_introduction
```

## Front
How can one calculate the row / column averages of a matrix?

## Back
<b>row average</b><div>\[\left[\begin{array}{c}
\frac{1}{m} \sum_{i=1}^{m} X_{1, i} \\
\vdots \\
\frac{1}{m} \sum_{i=1}^{m} X_{n, i}
\end{array}\right]=\boldsymbol{X}\left[\begin{array}{c}
\frac{1}{m} \\
\vdots \\
\frac{1}{m}
\end{array}\right]=\boldsymbol{X} \boldsymbol{a}, \quad \text { with } \boldsymbol{a}=\left[\begin{array}{c}
\frac{1}{m} \\
\vdots \\
\frac{1}{m}
\end{array}\right]\]
</div><div></div><div><b>column average</b></div><div>
</div><div>\[\left[\frac{1}{n} \sum_{i=1}^{n} X_{i, 1}, \ldots, \frac{1}{n} \sum_{i=1}^{n} X_{i, m}\right]=\left[\frac{1}{n}, \ldots, \frac{1}{n}\right] \boldsymbol{X}=\boldsymbol{b}^{T} \boldsymbol{X}, \text { with } \boldsymbol{b}=\left[\begin{array}{c}
\frac{1}{n} \\
\vdots \\
\frac{1}{n}
\end{array}\right]\]
</div>
