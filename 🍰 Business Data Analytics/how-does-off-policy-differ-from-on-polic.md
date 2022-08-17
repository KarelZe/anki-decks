## Note
nid: 1656170982888
model: Basic-02d89
tags: 09_rl, 09_rl_bda
markdown: false

### Front
How does <b>off-policy</b> differ from <b>on-policy</b>?

### Back
<ul>
  <li><b>Off-Policy:</b> Randomly try actions without consulting
  the currently assume optimal policy.
  <li><b>On-Policy:</b> Follow the current policy and update the
  results.
  <li><b>N-step DQN:</b> Perform n steps on-policy and then update.
  Speeds up the learning for small values of n.
</ul>
<div>
  <b>Practical difference:</b>
</div>
<div>
  Off-policy can use replay buffer even with old samples as the
  current action-value function is used. On-policy needs to sample
  training data from current model.
</div>
