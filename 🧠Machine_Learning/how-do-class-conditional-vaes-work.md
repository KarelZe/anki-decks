## Note
nid: 1656331383081
model: Basic-02d89
tags: 12_var_ml
markdown: false

### Front
How do class-conditional VAEs work?

### Back
Class-conditional VAE provides the labels to both the encoder and the decoder.

Since the latent code \(\boldsymbol{z}\) no longer has to model the image category, it can focus on modeling the stylistic features e.g., handwriting style.

<b>Visualization:</b>
<img src="paste-468dbade8009e79d3c211d1849d8d6e4f1105c3f.jpg">
