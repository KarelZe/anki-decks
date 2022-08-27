## Note
nid: 1655651875514
model: Basic-02d89-e0e22
tags: bda::07_unsupervised_learning
markdown: false

### Front
How are <b>principal components</b> selected? How are the
transformed coordinates calculated?

### Back
Select \(m\) principal components. In the new orthonormal basis
\(\left(u_{i}^{T} u_{j}=0\right.\), and
\(\left.\left\|u_{i}\right\|=1\right)\), any point \(x\) has new
coordinates \(a\) : \[x=a_{1} u_{1}+a_{2} u_{2}+\cdots+a_{m}
u_{m}=U a\] These coordinates can be obtained by \(a=U^{T} x\)
<b>Visualization:</b> <img src="15554174747084_pca3_1.png">
