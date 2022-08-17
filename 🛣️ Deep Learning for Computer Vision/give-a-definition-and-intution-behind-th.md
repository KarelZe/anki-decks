## Note
nid: 1651482414766
model: Basic-02d89
tags: 02_basics_nn_dlcv
markdown: false

### Front
Give a definition and intution behind the \(\ell_1\) and \(\ell_2\) loss

### Back
\(\ell_1\) -Loss (<b>Mean Average Error</b>):
\[
L(x, y)=\sum_{j}\left(y_{j}-x_{j}\right)
\]
\(\ell_2\) -Loss (<b>Mean Square Error</b>):
\[
L(x, y)=\sum_{j}\left(y_{j}-x_{j}\right)^{2}
\]

Intuition:
Predicting a one or multiple continuous quantities \(\boldsymbol{y}_{1} \ldots \boldsymbol{y}_{n}\) Minimize the distance between the predicted value \(\boldsymbol{x}_{j}\) true values \(\boldsymbol{y}_{j}\)
