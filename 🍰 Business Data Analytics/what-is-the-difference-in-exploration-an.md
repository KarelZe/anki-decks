## Note
nid: 1656173165216
model: Basic-02d89
tags: 09_rl, 09_rl_bda
markdown: false

### Front
What is the difference in<b> Exploration</b> and <b>Exploitation</b> in <b>Reinforcement Learning</b>?

### Back
<ul>
  <li>At the beginning there is little experience in the
  environment. Agent shouldn't choose actions abes on th
  eaction-value function but randomly. Exploration parameter
  determines the probability of a random action.
  <li><b>Exploration</b> should diminish throughout the training
  (\(\varepsilon\)-greedy method)
  <li>Once the action-value is sufficiently understood, it can be
  <b>exploited</b>.
</ul>
