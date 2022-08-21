## Note
nid: 1620897631564
model: Basic-b122e
tags: 09_lecture
markdown: false

### Front
How does a Maximal Margin Classifier work? What is being maximized?

### Back
Among all separating hyperplanes, find the ones that make the biggest gap or margin between two classes.<div>
</div><div>Constrained optimization problem:</div><div>
</div><div>\[\begin{array}{r}
\text { maximize } M \text { subject to } \sum_{j=1}^{p} \beta_{j}^{2}=1 \\
y_{i}\left(\beta_{0}+\beta_{1} x_{i 1}+\ldots+\beta_{p} x_{i p} \geq M \text { for all } i=1, \ldots, N\right.
\end{array}\]
</div>
