# Note
```
guid: I^)=h#d^bt
notetype: Basic-d7a3e-4ce08
```

### Tags
```
adv_ml::08_clustering
```

## Front
Give a <b>recipe</b> for computing <b>principal components</b>.

## Back
Suppose we have a \(n \times p\) data set \(X\). Since we are only interested in variance, we assume that each of the variables in \(X\) has been
centered to have mean zero (that is, the column means of \(X\) are zero).
<div>
</div><div>We then look for the linear combination of the sample feature values of the form

\[P C A_{i 1}=\phi_{11} X_{i 1}+\phi_{21} X_{i 2}+\ldots+\phi_{P 1} X_{i P}\]</div><div>
for \(i=1, \ldots, n\) that has largest sample variance, subject to the constraint that \(\sum_{j=1}^{p} \phi_{j 1}^{2}=1\).
</div><div>
</div><div>Since each of the \(x_{i j}\) has mean zero, then so does \(\text{PCA}_{i 1}\) (for any values of \(\phi_{j 1}\) ). Hence the sample variance of the \(P C A_{i 1}\) can be written as \(\frac{1}{n} \sum_{j=1}^{p} \text{PCA}_{i 1}^{2}\).
</div><div>
</div><div>Plugging into the last equation the first principal component loading vector solves the optimization problem
maximize </div><div>
</div><div>\[\frac{1}{n} \sum_{i=1}^{n}\left(\sum_{j=1}^{P} \phi_{j 1} x_{i j}\right)^{2}\text{ subject to }\sum_{j=1}^{p} \phi_{j 1}^{2}=1\]</div><div>
</div><div>This problem can be solved via a singular-value decomposition of the matrix \(X\), a standard technique in linear algebra.</div><div>
We refer to \(\text{PCA}_{1}\) as the first principal component, with realized
values \(\text{pca}_{11}, \ldots \text{pca}_{n 1}\)
</div><div>
</div><div>The second principal component is the linear combination of \(X_{1}, X_{2}, \ldots, X_{P}\) that has maximal variance among all linear combinations that are uncorrelated with \(\text{PCA}_{1}\).
The second principal component scores \(z_{12}, z_{22}, \ldots, z_{n 2}\) take the form

\[\text{PCA}_{i 2}=\phi_{12} X_{i 1}+\phi_{22} X_{i 2}+\ldots+\phi_{P 2} X_{i P}\]

where \(\phi_{2}\) is the second principal component loading vector, with elements \(\phi_{12}, \ldots \phi_{p 2}\)
It turns out that constraining \(\text{PCA}_{2}\) to be uncorrelated with \(\text{PCA}_{1}\) is equivalent to constraining the direction \(\phi_{2}\) to be orthogonal to the direction \(\phi_{1}\).</div>
