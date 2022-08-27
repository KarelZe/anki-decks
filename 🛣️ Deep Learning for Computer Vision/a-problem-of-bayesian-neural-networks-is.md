## Note
nid: 1659863560895
model: Basic-02d89-e0e22
tags: dl_cv::12_adv_topics
markdown: false

### Front
A problem of Bayesian neural networks is that the integral can not  be solved analytically:
\[p\left(\mathbf{y}^{*} \mid \mathbf{x}^{*}, \mathbf{X}, \mathbf{Y}\right)=\int p\left(\mathbf{y}^{*} \mid \mathbf{x}^{*}, \omega\right) p(\omega \mid \mathbf{X}, \mathbf{Y}) \mathrm{d} \omega\]with \(X, Y\) : training data (inputs and outputs),
\(x^{*}:\) a new test point (input),
\(y^{*}:\) prediction for \(\mathrm{X}^{*}\) (output),
\(\omega:\) model parameters

How can it be solved?

### Back
Approximating \(p(\omega \mid X, Y)\) with an „easier" variational distribution \(q_{\theta}(\omega)\):
\[\begin{equation}
\begin{aligned}
&p\left(\mathbf{y}^{*} \mid \mathbf{x}^{*}, \mathbf{X}, \mathbf{Y}\right)=\int p\left(\mathbf{y}^{*} \mid \mathbf{x}^{*}, \omega\right) p(\omega \mid \mathbf{X}, \mathbf{Y}) \mathrm{d} \omega\\
&\approx \int p\left(\mathbf{y}^{*} \mid \mathbf{x}^{*}, \omega\right) q_{\theta}(\omega) \mathrm{d} \omega\\
&\approx \frac{1}{T} \sum_{t=1}^{T} p\left(\mathbf{y}^{*} \mid \mathbf{x}^{*}, \omega_{t}\right), \text { with } \omega_{t} \sim q_{\theta}(\omega)
\end{aligned}
\end{equation}\]
