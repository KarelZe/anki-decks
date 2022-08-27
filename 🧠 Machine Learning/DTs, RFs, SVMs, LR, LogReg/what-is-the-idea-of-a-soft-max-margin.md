## Note
nid: 1629026906858
model: Basic-d7a3e-4ce08
tags: checklater, ml::08_svm
markdown: false

### Front
What is the idea of a <b>soft max-margin</b>?

### Back
One introduces <b>slack variables </b>\(\xi_{i}\), so that some margin violations are tolerated. <div>
</div><div>However, a punishment term is applied for a large number of slack variables.</div><div>
</div><div>\(\begin{aligned}
\operatorname{argmin}_{\mathbf{w}, \boldsymbol{\xi}} &\|\mathbf{w}\|^{2}+C \sum_{i}^{N} \xi_{i}, \\
\text { s.t. } & y_{i}\left(\mathbf{w}^{T} \mathbf{x}_{i}+b\right) \geq 1-\xi_{i}, \quad \xi_{i} \geq 0
\end{aligned}\)
</div><div>
</div>
