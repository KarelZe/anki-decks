## Note
nid: 1607452836085
model: Basic-d7a3e-4ce08
tags: checklater, ml::02_linear_classification
markdown: false

### Front
<p>How should the <b>Learning Rate</b> / <b>Step size</b> for
<b>Stochastic Gradient Descent</b> be chosen?

### Back
<div>
  <div>
    <ul>
      <li>Assymptotically approach the optimum
      <li>Instead of “wiggling” around optimum
    </ul>
  </div>
</div>
<p>Standard in <b>SGD</b> is to use diminishing step sizes, e.g.,
\(\eta_{t}=\frac{1}{t}\)
