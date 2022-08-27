## Note
nid: 1655649266637
model: Basic-02d89-e0e22
tags: bda::07_unsupervised_learning
markdown: false

### Front
How is the covariance matrix defined? What are its diagonal elements? What are its off-diagonal elements?

### Back
\[C=\left[\begin{array}{ccc} \operatorname{cov}\left(X_{1},
X_{1}\right) & \cdots & \operatorname{cov}\left(X_{1}, X_{m}\right)
\\ \vdots & \ddots & \vdots \\ \operatorname{cov}\left(X_{m},
X_{1}\right) & \cdots & \operatorname{cov}\left(X_{m}, X_{m}\right)
\end{array}\right]\] With: Standardized feature vector
\(X_{j}=\left[\begin{array}{c}x_{1 j} \\ x_{2 j} \\ \cdots \\ x_{n
j}\end{array}\right]\) Mean \(\quad \bar{X}_{j}=\frac{1}{n}
\sum_{i=1}^{n} x_{i j}\) Variance \(\quad
\operatorname{var}\left(X_{j}\right)=\frac{1}{n-1}
\sum_{i=1}^{n}\left(x_{i j}-\bar{x}_{j}\right)^{2}\) Covariance
\(\quad \operatorname{cov}\left(X_{j}, X_{k}\right)=\frac{1}{n-1}
\sum_{i=1}^{n}\left(x_{i j}-\bar{x}_{j}\right)\left(x_{i
k}-\bar{x}_{k}\right)\) \(\operatorname{cor}\left(X_{j},
X_{k}\right)=\frac{\operatorname{cov}\left(X_{j},
X_{k}\right)}{\sqrt{\operatorname{var}\left(X_{j}\right)
\operatorname{var}\left(X_{k}\right)}}\) <b>Elements:</b> Diagonal
elements are \(\operatorname{cov}\left(X_{i},
X_{i}\right)=\operatorname{var}\left(X_{i}\right)\) Off-diagonal
elements are \(\operatorname{cov}\left(X_{i},
X_{j}\right)=\operatorname{cov}\left(X_{j}, X_{i}\right)\)
