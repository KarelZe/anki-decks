## Note
nid: 1659861994547
model: Basic-02d89-e0e22
tags: dl_cv::12_adv_topics
markdown: false

### Front
What is problematic about Bayesian Neural Networks?

### Back
Distribution cannot be evaluated analytically:
\[p\left(\mathbf{y}^{*} \mid \mathbf{x}^{*}, \mathbf{X}, \mathbf{Y}\right)=\int p\left(\mathbf{y}^{*} \mid \mathbf{x}^{*}, \omega\right) p(\omega \mid \mathbf{X}, \mathbf{Y}) \mathrm{d} \omega\]with \(X, Y\) : training data (inputs and outputs),
\(x^{*}:\) a new test point (input),
\(y^{*}:\) prediction for \(\mathrm{X}^{*}\) (output),
\(\omega:\) model parameters
