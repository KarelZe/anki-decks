# Note
```
guid: JpVjd2$1qp
notetype: Basic-02d89-e0e22
```

### Tags
```
ml::12_var_ae
```

## Front
What is amoritzed variational interference? Also explain the intuition behind it.

## Back
<b>Definition:</b> Instead of using an individual auxiliary
distribution \(q_{i}(\boldsymbol{z})\) per data-point
\(\boldsymbol{x}_{i}\), we can use an "amortized" distribution
\(q_{\boldsymbol{\phi}}\left(\boldsymbol{z} \mid
\boldsymbol{x}_{i}\right)\) that is given by a DNN:
\[\mathcal{L}(q, p)=\frac{1}{N} \sum_{i} \int
q_{\boldsymbol{\phi}}\left(\boldsymbol{z} \mid
\boldsymbol{x}_{i}\right) \log
p_{\boldsymbol{\varphi}}\left(\boldsymbol{x}_{i} \mid
\boldsymbol{z}\right) d
\boldsymbol{z}-\mathrm{KL}\left(q_{\boldsymbol{\phi}}\left(\boldsymbol{z}
\mid \boldsymbol{x}_{i}\right)||
p_{\boldsymbol{\varphi}}(\boldsymbol{z})\right)\]This is the
standard objective used for variational auto-encoders (VAE).
Encoder \(q_{\phi}(\boldsymbol{z} \mid \boldsymbol{x})\), Decoder
\(p_{\varphi}(\boldsymbol{x} \mid z)\), and Latent Prior
\(p_{\boldsymbol{\varphi}}(\boldsymbol{z})\). <b>Intuition:</b>
Amortized VI is the idea that instead of optimizing a set of free
parameters, we can introduce a parameterized function that maps
from observation space to the parameters of the approximate
posterior distribution. In practice, we might (for example)
introduce a neural network that accepts an observation as input,
and outputs the mean and variance parameter for the latent variable
associated with that observation. We can then optimize the
parameters of this neural network instead of the individual
parameters of each observation.
