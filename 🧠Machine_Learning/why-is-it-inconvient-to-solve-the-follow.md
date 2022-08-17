## Note
nid: 1628936839479
model: Basic-d7a3e
tags: 08_svm
markdown: false

### Front
Why is it inconvient to solve the following optimization for SMV?
<div>
  \[\begin{aligned} \operatorname{argmax}_{\mathbf{w}}
  \frac{2}{\|\mathbf{w}\|}, \\ \text { s.t. } \quad &
  \mathbf{w}^{T} \mathbf{x}_{i}+b\left\{\begin{array}{l} \geq+1, &
  \text { falls } y_{i}=+1 \\ \leq-1, & \text { falls } y_{i}=-1
  \end{array}\right. \end{aligned}\]
</div>

### Back
The above is hard to solve. It's easier to solve it as a quadratic optimization problem.
