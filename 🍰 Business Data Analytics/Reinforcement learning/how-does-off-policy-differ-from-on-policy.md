# Note
```
guid: t>t?RyA6NR
notetype: Basic-02d89-e0e22
```

### Tags
```
bda::09_rl
```

## Front
How does <b>off-policy</b> differ from <b>on-policy</b>?

## Back
<ul><li><b>Off-Policy:</b> Randomly try actions without consulting the currently assume optimal policy.</li><li><b>On-Policy:</b> Follow the current policy and update the results.</li><li><b>N-step DQN:</b> Perform n steps on-policy and then update. Speeds up the learning for small values of n.</li></ul><div><b>Practical difference:</b></div><div>Off-policy can use replay buffer even with old samples as the current action-value function is used. On-policy needs to sample training data from current model.</div>
