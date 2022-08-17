## Note
nid: 1656176202025
model: Basic-02d89
tags: 09_rl, 09_rl_bda
markdown: false

### Front
What is the <b>idea</b> of the <b>proximal policy optimization</b>?

### Back
The policy update is constrained to a trust region, to avoid large
deviations in update steps. PPO is an on-policy algorithm.
Therefore, it does not use a replay buffer and actions are directly
evaluated. PPO allows only clipped updates to the policy. The
objective function is defined as \[L^{C L I
P}(\theta)=\hat{\mathbb{E}}_{t}\left[\min \left(r_{t}(\theta)
\hat{A}_{t}, \operatorname{clip}\left(r_{t}(\theta), 1-\epsilon,
1+\epsilon\right) \hat{A}_{t}\right)\right]\] With \(\quad
r_{t}(\theta)=\frac{\pi_{\theta}\left(a_{t} \mid
s_{t}\right)}{\pi_{\theta_{\text {old }}}\left(a_{t} \mid
s_{t}\right)}\) <img src= 
"paste-f634d9b72146aeb365d3993878788c978852ff78.jpg">
