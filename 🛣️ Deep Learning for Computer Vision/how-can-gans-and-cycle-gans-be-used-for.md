## Note
nid: 1659868725121
model: Basic-02d89
tags: 12_adv_topics_dl_cv
markdown: false

### Front
How can <b>GANs</b> and <b>Cycle-GANs</b> be used for <b>domain
adaption</b>.

### Back
<b>GANs
</b>An adversarial network is tasked with discriminating between source and target features / outputs.
Segmentation model is incentiviced to align output and feature distributions of source and target domain by the discriminator network.
<img src="paste-a5687148b8fa9a62ef83709897e479f1935ad9d0.jpg">

<b>Cycle-GANs</b>
Translate images from source domain to target domain and back. 
The segmentation model is then trained on the translated source images and their corresponding segmentation masks. Consistency loss is extended to preserve class information.
<img src="paste-6017065839defba2851871cadf0ef1aa4f311a21.jpg">
