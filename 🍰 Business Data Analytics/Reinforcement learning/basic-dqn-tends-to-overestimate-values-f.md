## Note
nid: 1656171120429
model: Basic-02d89-e0e22
tags: bda::09_rl
markdown: false

### Front
Basic DQN tends to overestimate values for \(Q\) due to the max operation in the Bellman equation. How can it be adressed?

### Back
Double <b>DQN architecture</b>.\(Q\left(s_{t}, a_{t}\right)=r_{t}+\gamma \max _{a} Q^{\prime}\left(s_{t+1}, \underset{a}{\arg \max } Q\left(s_{t+1}, a\right)\right)\)
