## Note
nid: 1629478655741
model: Basic-d7a3e
tags: 00_klausurfragen
markdown: false

### Front
You are given the following optimization problem:
\[
\begin{aligned}
\underset{a}{\operatorname{argmax}} & \quad a^{2} h \\
\text { s.t. } & S_{\max } \geq 2 a^{2}+4 a h
\end{aligned}
\]
Write down the Lagrangian. Derive the optimal value for \(a\) depending on your lagrangian multiplier.

### Back
\[
\begin{aligned}
L &=a^{2} h+\lambda\left(S_{\max }-2 a^{2}-4 a h\right) \\
\frac{d L}{d a} &=2 a h-4 \lambda a-4 \lambda h \\
a^{*} &=\frac{4 \lambda h}{2 h-4 \lambda}
\end{aligned}
\]
(The sign in the Lagrangian may change. But the following equations should be correct according to the Lagrangian.)
