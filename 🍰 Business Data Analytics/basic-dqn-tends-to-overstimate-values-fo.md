## Note
nid: 1656171120429
model: Basic-02d89
tags: 09_rl, 09_rl_bda
markdown: false

### Front
Basic DQN tends to overstimate values for \(Q\) due to the max operation in the Bellman equation. How can it be adressed?

### Back
Double <b>DQN architecture</b>.\(Q\left(s_{t},
a_{t}\right)=r_{t}+\gamma \max _{a} Q^{\prime}\left(s_{t+1},
\underset{a}{\arg \max } Q\left(s_{t+1}, a\right)\right)\)
