# Note
```
guid: Dbo$]gml9@
notetype: Basic-d7a3e-4ce08
```

### Tags
```
ml::08_svm
```

## Front
Why is it inconvient to solve the following optimization for SMV?<div>
</div><div>\[\begin{aligned}
\operatorname{argmax}_{\mathbf{w}} \frac{2}{\|\mathbf{w}\|}, \\
\text { s.t. } \quad & \mathbf{w}^{T} \mathbf{x}_{i}+b\left\{\begin{array}{l}
\geq+1, & \text { falls } y_{i}=+1 \\
\leq-1, & \text { falls } y_{i}=-1
\end{array}\right.
\end{aligned}\]
</div>

## Back
The above is hard to solve. It's easier to solve it as a quadratic optimization problem.
