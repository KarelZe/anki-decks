# Note
```
guid: JP%V{%3U;G
notetype: Basic-d7a3e-4ce08
```

### Tags
```
checklater
ml::08_svm
```

## Front
Rewrite the following constrained optimization problem of a SVM to an unconstrained one.<div>
</div><div>\[\operatorname{argmin}_{\mathbf{w}, \boldsymbol{\xi}} \quad\|\mathbf{w}\|^{2}+C \sum_{i}^{N} \xi_{i}, \quad \text { s.t. } \quad y_{i}\left(\mathbf{w}^{T} \mathbf{x}_{i}+b\right) \geq 1-\xi_{i}, \quad \xi_{i} \geq 0\]
</div>

## Back
Rewrite constraints: \(\xi_{i} \geq 1-y_{i}\left(\mathbf{w}^{T} \mathbf{x}_{i}+b\right)=1-y_{i} f\left(\boldsymbol{x}_{i}\right)\)<div>
Together with \(\xi_{i} \geq 0\) this results in \(\xi_{i}=\max \left(0,1-y_{i} f\left(\boldsymbol{x}_{i}\right)\right)\) (given that \(\xi_{i}\) should be minimized)</div><div>
</div><div>unconstrained optimization (over w):</div><div>
</div><div>\(\operatorname{argmin}_{\mathbf{w}} \underbrace{\|\mathbf{w}\|^{2}}_{\text {regularization }}+C \underbrace{\sum_{i=1}^{N} \max \left(0,1-y_{i} f\left(\boldsymbol{x}_{i}\right)\right)}_{\text {loss function }}\)
</div>
