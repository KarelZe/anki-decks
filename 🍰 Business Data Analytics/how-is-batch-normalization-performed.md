## Note
nid: 1653203343925
model: Basic-02d89
tags: 06_trainining_tuning_bda
markdown: false

### Front
How is <b>Batch Normalization</b> performed?

### Back
\(\hat{x}^{(i)}=\frac{x^{(i)}-\mu_{B}}{\sqrt{\sigma_{B}^{2}+\epsilon}}, z^{(i)}=\gamma \hat{x}^{(i)}+\beta\) (scaled and shifted version of layer input)
