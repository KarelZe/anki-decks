# Note
```
guid: CrWEoVc!gf
notetype: Basic-02d89-e0e22
```

### Tags
```
bda::09_rl
```

## Front
Explain the idea of <b>policy gradients</b> in Reinforcement
Learning.

## Back
The policy is what we are looking for when we are solving a reinforcement learning problem. However, especially if the action space is not discrete, we need other methods to determine the optimal policy.
A policy describes an agent's behavior by mapping states to a probability distribution over the actions.

The policy gradient is then determined by
\[\begin{aligned}
\nabla_{\theta^{\mu}} J & \approx \mathbb{E}_{s_{t} \sim \rho^{\beta}}\left[\left.\nabla_{\theta^{\mu}} Q\left(s, a \mid \theta^{Q}\right)\right|_{s=s_{t}, a=\mu\left(s_{t} \mid \theta^{\mu}\right)}\right] \\
&=\mathbb{E}_{s_{t} \sim \rho^{\beta}}\left[\left.\left.\nabla_{a} Q\left(s, a \mid \theta^{Q}\right)\right|_{s=s_{t}, a=\mu\left(s_{t}\right)} \nabla_{\theta_{\mu}} \mu\left(s \mid \theta^{\mu}\right)\right|_{s=s_{t}}\right]
\end{aligned}\]
