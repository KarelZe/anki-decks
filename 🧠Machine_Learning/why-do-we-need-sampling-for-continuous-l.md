## Note
nid: 1631076797968
model: Basic-d7a3e
tags: 06_em_for_dim_reduction, ultra
markdown: false

### Front
Why do we need sampling for continuous latent variables in the M-Step of the EM algorithm?

### Back
<div>
  <div>
    <ul>
      <li>Typically it is not feasable to compute the integral in
      the Maximization step with continous latent variables, as no
      analytical solutions exist for the integral.
      <li>Instead a MC estimation is used to calculate the lower
      bound.
    </ul>
  </div>
</div>
