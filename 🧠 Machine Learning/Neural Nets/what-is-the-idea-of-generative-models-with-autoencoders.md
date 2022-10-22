# Note
```
guid: O7U<?,P7ed
notetype: Basic-02d89-e0e22
```

### Tags
```
ml::12_var_ae
```

## Front
What is the idea of <b>generative models</b> with
<b>AutoEncoders</b>.

## Back
Consider training a generator network with maximum likelihood.
\[p(\boldsymbol{x})=\int p(\boldsymbol{z}) p(\boldsymbol{x} \mid
\boldsymbol{z}) d \boldsymbol{z}\]If \(z\) is low-dimensional and
the decoder is deterministic, then \(p(x)=0\) almost everywhere!
The model only generates samples over a low-dimensional
sub-manifold of \(X\). Define a noisy observation model, e.g.
\[p(\boldsymbol{x} \mid
\boldsymbol{z})=\mathcal{N}\left(\boldsymbol{x} \mid
\boldsymbol{\mu}_{\boldsymbol{\theta}}(\boldsymbol{z}), \sigma^{2}
\boldsymbol{I}\right)\]where
\(\boldsymbol{\mu}_{\boldsymbol{\theta}}(\boldsymbol{z})\) is the
function computed by the decoder with parameters \(\theta\). We now
also have an uncertainty estimate. <b>Visualization:</b> <img src="paste-1b43f9bd5b466f454e5a45db84b0ef4b6e6bcff3.jpg">
