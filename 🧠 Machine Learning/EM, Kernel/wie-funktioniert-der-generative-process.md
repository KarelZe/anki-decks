## Note
nid: 1610226042283
model: Basic-d7a3e-4ce08
tags: ml::06_em_for_dim_reduction, ultra
markdown: false

### Front
<p>Wie funktioniert der <b>Generative Process</b> bei <b>PPCA</b>?

### Back
<div>
  <div>
    <ol>
      <li>Sample latent variable \[ \boldsymbol{z} \sim
      \mathcal{N}(\mathbf{0}, \boldsymbol{I}) \]
      <li>Linearly project to high-\(D\) space \[
      \boldsymbol{y}=\boldsymbol{W} \boldsymbol{z}+\boldsymbol{\mu}
      \]
      <li>Sample noise \[ \epsilon \sim
      \mathcal{N}\left(\mathbf{0}, \sigma^{2} \boldsymbol{I}\right)
      \]
      <li>Add noise to obtain \(\mathbf{x}\) \[
      \boldsymbol{x}=\boldsymbol{y}+\boldsymbol{\epsilon} \]
    </ol>
  </div>
</div>
<p><img src="12wgBdw7BJtcqzLcw4vx.png" style="width: 366px;">
