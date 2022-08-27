## Note
nid: 1656175014764
model: Basic-02d89-e0e22
tags: bda::09_rl
markdown: false

### Front
What are the <b>three tricks</b> used in the<b> TD3 algorithm</b>?

### Back
<b>Trick One: Clipped Double-Q Learning. </b>TD3 learns two Q-functions instead of one (hence "twin"), and uses the smaller of the two Q-values to form the targets in the Bellman error loss functions.
\[y\left(r, s^{\prime}, d\right)=r+\gamma(1-d) \min _{i=1,2} Q_{\phi_{i, t a s \mathbf{g}}}\left(s^{\prime}, a^{\prime}\left(s^{\prime}\right)\right),\]
\[L\left(\phi_{1}, \mathcal{D}\right)=\underset{\left(s, a, r, s^{\prime}, d\right) \sim \mathcal{D}}{\mathrm{E}}\left[\left(Q_{\phi_{1}}(s, a)-y\left(r, s^{\prime}, d\right)\right)^{2}\right], \quad L\left(\phi_{2}, \mathcal{D}\right)=\underset{\left(s, a, r, s^{\prime}, d\right) \sim \mathcal{D}}{\mathrm{E}}\left[\left(Q_{\phi_{2}}(s, a)-y\left(r, s^{\prime}, d\right)\right)^{2}\right]\]

<b>Trick Two: "Delayed" Policy Updates.</b> TD3 updates the policy (and target networks) less frequently than the \(Q\)-function. The paper recommends one policy update for every two Q-function updates.
<img src="paste-4627c50931ec3706181a36e757bc741b264f7dbd.jpg">

<b>Trick Three: Target Policy Smoothing. </b>TD3 adds noise to the target action, to make it harder for the policy to exploit \(Q\)-function errors by smoothing out \(Q\) along changes in action.

\[
a^{\prime}\left(s^{\prime}\right)=\operatorname{clip}\left(\mu_{\theta_{\text {tasz }}}\left(s^{\prime}\right)+\operatorname{clip}(\epsilon,-c, c), a_{\text {Low }}, a_{H i g h}\right), \quad \epsilon \sim \mathcal{N}(0, \sigma)
\]
