## Note
nid: 1651482755295
model: Basic-02d89
tags: 02_basics_nn_dlcv
markdown: false

### Front
Give a <b>definition</b> and <b>intuition</b> for the <b>Triplet
loss</b>.

### Back
Loss function:
\[
\sum_{(a, p, n) \in T} \max \left\{0, \alpha-\left\|\mathbf{x}_{a}-\mathbf{x}_{n}\right\|_{2}^{2}+\left\|\mathbf{x}_{a}-\mathbf{x}_{p}\right\|_{2}^{2}\right\}
\]
\(a\) is the margin constant (usually set to 1)

<b>Intuition:</b>
A model for measuring the distance (or similarity) between objects.

Find a model, that would produce a representation \(\left\{x_{a}, x_{n}, x_{p}\right\}\), so that the distance between \(x_{a}\) and \(x_{p}\) is small and the distance between \(x_{a}\) and \(x_{n}\) is large

<b>Example:</b>
Input: three images (anchor image, positive (similar) and a negative (dissimilar) example

<img src="paste-696e6d8126630b4d690ddf5b3361e94b0e1635e9.jpg">
