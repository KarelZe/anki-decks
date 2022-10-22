# Note
```
guid: u?5qh[a]6Z
notetype: Basic-02d89-e0e22
```

### Tags
```
ml::12_var_ae
```

## Front
What is the <b>reparametrization trick</b>?

## Back
<b>Reparametrization Trick:</b> \[\int p_{\theta}(\boldsymbol{x})
f(\boldsymbol{x}) d \boldsymbol{x}=\int q(\boldsymbol{\xi})
f\left(\boldsymbol{h}_{\theta}(\boldsymbol{\xi})\right) d
\boldsymbol{\xi}\] <b>Reparametrized Gradient:</b>
\[\nabla_{\boldsymbol{\theta}}
\mathbb{E}_{p_{\boldsymbol{\theta}}}[f(\boldsymbol{x})]=\nabla_{\boldsymbol{\theta}}
\int q(\boldsymbol{\xi})
f\left(\boldsymbol{h}_{\theta}(\boldsymbol{\xi})\right) d
\boldsymbol{\xi}=\int q(\boldsymbol{\xi}) \frac{\partial
\boldsymbol{h}_{\boldsymbol{\theta}}}{\partial
\boldsymbol{\theta}}(\boldsymbol{\xi}) \frac{\partial f}{\partial
\boldsymbol{x}}\left(\boldsymbol{h}_{\boldsymbol{\theta}}(\boldsymbol{\xi})\right)
d \boldsymbol{\xi}\] We can now use the gradient \(\frac{\partial
f}{\partial \boldsymbol{x}}\) to compute
\(\nabla_{\boldsymbol{\theta}}
\mathbb{E}_{p_{\boldsymbol{\theta}}}[f(\boldsymbol{x})]\) !
<b>Example:</b> <img src="paste-5026942aa1e0be8da22f199fd698be3cfa26e418.jpg">
