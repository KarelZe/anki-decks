## Note
nid: 1631171939109
model: Basic-d7a3e-4ce08
tags: ml::09_bayesian_learning
markdown: false

### Front
How can we derive a <b>Gaussian Process</b> using <b>Gaussian
propagation</b>?

### Back
A Gaussian proces over \(N\) function evaluations
\(\boldsymbol{t}=\left[t_{1}, \ldots, t_{N}\right]^{T}\) by the
mean and covariance.
<div>
  \(p(\boldsymbol{t} \mid
  \boldsymbol{X})=\mathcal{N}(\boldsymbol{t} \mid \mathbf{0},
  \boldsymbol{K}) \quad\) with \(\quad
  \boldsymbol{K}=\left[\begin{array}{ccc}k\left(\boldsymbol{x}_{1},
  \boldsymbol{x}_{1}\right) & \ldots & k\left(\boldsymbol{x}_{1},
  \boldsymbol{x}_{N}\right) \\ \vdots & \ddots & \vdots \\
  k\left(\boldsymbol{x}_{N}, \boldsymbol{x}_{1}\right) & \ldots &
  k\left(\boldsymbol{x}_{N},
  \boldsymbol{x}_{N}\right)\end{array}\right]\)
</div>
<div>
  We get the Gaussian distribution over \(\boldsymbol{y}\).
</div>
<div>
  \(\begin{aligned} p(\boldsymbol{y} \mid \boldsymbol{X})
  &=\int p(\boldsymbol{y} \mid \boldsymbol{t}) p(\boldsymbol{t}
  \mid \boldsymbol{X}) d \boldsymbol{t} \\ &=\int
  \mathcal{N}\left(\boldsymbol{y} \mid \boldsymbol{t},
  \sigma_{y}^{2} \boldsymbol{I}\right) \mathcal{N}(\boldsymbol{t}
  \mid \mathbf{0}, \boldsymbol{K}) d \boldsymbol{t} \ldots \text {
  Gaussian propagation } \\ &=\mathcal{N}\left(\boldsymbol{y}
  \mid \mathbf{0}, \boldsymbol{K}+\sigma_{y}^{2}
  \boldsymbol{I}\right) \end{aligned}\)
</div>
<div>
  For a new dat-point y^{*} we can obtain the joint distribution
  over function values by:
</div>
<div>
  \(p\left(\left[\begin{array}{c}y \\ y^{*}\end{array}\right]
  \mid\left[\begin{array}{l}\boldsymbol{X} \\
  \boldsymbol{x}^{*}\end{array}\right]\right)=\mathcal{N}\left(\left[\begin{array}{c}\boldsymbol{y}
  \\ y^{*}\end{array}\right]
  \mid\left[\begin{array}{cc}\boldsymbol{K}+\sigma_{y}^{2}
  \boldsymbol{I} & \boldsymbol{k}_{x^{*}} \\
  \boldsymbol{k}_{\boldsymbol{x}^{*}}^{T} &
  k^{*}+\sigma_{y}^{2}\end{array}\right]\right),\)
</div>
<div>
  with \(\boldsymbol{K} \ldots\) kernel matrix,
  \(k_{\boldsymbol{x}^{\star}}=\left[k\left(\boldsymbol{x}_{1},
  x^{*}\right), \ldots, k\left(\boldsymbol{x}_{N},
  \boldsymbol{x}^{*}\right)\right]^{T} \ldots\) kernel vector,
  \(k^{*}=k\left(\boldsymbol{x}^{*}, \boldsymbol{x}^{*}\right)\)
</div>
<div>
  By conditioning on \(y\) we get the predictive (Gaussian)
  distributions with:
</div>
<div>
  mean:
  \(\mu\left(\boldsymbol{x}^{*}\right)=\boldsymbol{k}_{\boldsymbol{x}^{*}}^{T}\left(\boldsymbol{K}+\sigma_{y}^{2}
  \boldsymbol{I}\right)^{-1} \boldsymbol{y}\)
</div>
<div>
  Variance:
  \(\sigma^{2}\left(\boldsymbol{x}^{*}\right)=k^{*}+\sigma_{y}^{2}-\boldsymbol{k}_{\boldsymbol{x}^{*}}^{T}\left(\boldsymbol{K}+\sigma_{y}^{2}
  \boldsymbol{I}\right)^{-1} \boldsymbol{k}_{\boldsymbol{x}^{*}}\)
</div>
