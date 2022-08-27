## Note
nid: 1652348520460
model: Basic-02d89-e0e22
tags: bda::06_trainining_tuning
markdown: false

### Front
Define \(\ell_1\) and \(\ell_2\) regularization.

### Back
\(\ell_2\)-Reguluarization (Ridge)
\[\mathcal{J}\left(W^{l}, b^{l}\right)=\frac{1}{m} \sum_{i=1}^{m} \mathcal{L}\left(y^{(i)}, y^{(i)}\right)+\frac{\lambda}{2 m} \sum_{l=1}^{l}\left\|W^{l}\right\|_{2}^{2}, \text { with }\left\|w^{i}\right\|_{2}^{2}=\sum_{j=1}^{n} w_{j}^{2}=w^{T} w\]
\(\ell_1\)-Reguluarization (LASSO)
\[\frac{\lambda}{2 m} \sum_{j=1}^{n}\left|w_{j}\right|=\|w\|_{1}\]
