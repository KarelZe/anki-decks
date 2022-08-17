## Note
nid: 1631170395859
model: Basic-d7a3e
tags: 09_bayesian_learning
markdown: false

### Front
What is the intuition of the <b>mean function</b> and the <b>covariance function</b> in a <b>Gaussian process</b>?

### Back
<div>
  <div>
    <ul>
      <li>Mean function evaluates our <strong>prior belief</strong>
      about the function:
      \(\mathbb{E}[f(\boldsymbol{x})]=m(\boldsymbol{x})\)
      <li>For simplicity, we will use \(m(x)=0\)
      <li>Covariance function evaluates how similar / correlated
      two function evaluations at inputs \(\boldsymbol{x},
      \boldsymbol{x}^{\prime}\) are:
      \(\mathbb{E}\left[f(\boldsymbol{x})
      f\left(\boldsymbol{x}^{\prime}\right)\right]=k\left(\boldsymbol{x},
      \boldsymbol{x}^{\prime}\right)\)
      <li>Covariance functions need to be positive definite. The
      covariance encodes the prior belief in the smoothness of a
      function.
    </ul>
  </div>
</div>
