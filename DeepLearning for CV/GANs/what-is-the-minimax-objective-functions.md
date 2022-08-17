## Note
nid: 1564143483982
model: Basic-66395
tags: 
markdown: false

### Front
What is the Minimax objective functions for GANs?

### Back
[$]
\min _{\theta_{g}} \max _{\theta_{d}}\left[\mathbb{E}_{x \sim p_{d a t a}} \log D_{\theta_{d}}(x)+\mathbb{E}_{z \sim p(z)} \log \left(1-D_{\theta_{d}}\left(G_{\theta_{g}}(z)\right)\right)\right]
[/$]
