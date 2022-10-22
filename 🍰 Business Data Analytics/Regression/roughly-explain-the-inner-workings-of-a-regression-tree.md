# Note
```
guid: H.)Q~pY~&=
notetype: Basic-02d89-e0e22
```

### Tags
```
bda::04_regression
```

## Front
Roughly explain the <b>inner workings</b> of a <b>regression
tree</b>.

## Back
Minimize the sum of squared residuals. \[\sum_{j=1}^{J} \sum_{i \in
R_{j}}\left(y_{i}-\hat{y}_{R_{j}}\right)^{2}\] Every cutoff point
is selected such that the following equation is minimized.
\[\begin{gathered} \sum_{i: x_{i} \in R_{1}(j,
s)}\left(y_{i}-\hat{y}_{R_{1}}\right)^{2}+\sum_{i: x_{i} \in
R_{2}(j, s)}\left(y_{i}-\hat{y}_{R_{2}}\right)^{2}, \\ R_{1}(j,
s)=\left\{X \mid X_{j} \leq s\right\} \text { and } R_{2}(j,
s)=\left\{X \mid X_{j}>s\right\} . \end{gathered}\] The value at
every leaf is the average of all data points in that leave.
<b>Visualization:</b> <img src="paste-959ae08ffa1fa1d6fc19637ecb27b3ee7b4ebd2d.jpg">
