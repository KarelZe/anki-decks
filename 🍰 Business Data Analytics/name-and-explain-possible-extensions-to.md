## Note
nid: 1656172768259
model: Basic-02d89
tags: 09_rl, 09_rl_bda
markdown: false

### Front
Name and explain <b>possible extensions</b> to <b>DQN</b>.

### Back
<ul><li><b>N-step DQN:</b> how to improve convergence speed and stability with a simple unrolling of the Bellman equation, and why it's not an ultimate solution Double DQN: how to deal with DQN overestimation of the values of the actions</li><li><b>Noisy networks:</b> how to make exploration more efficient by adding noise to the network weights</li><li>Prioritized replay buffer: why uniform sampling of our experience is not the best way to train</li><li><b>Dueling DQN:</b> how to improve convergence speed by making our network's architecture represent more closely the problem that we are solving</li><li><b>Categorical DQN: </b>how to go beyond the single expected value of the action and Work with full distributions</li></ul>
