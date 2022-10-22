# Note
```
guid: M5}V>&ihWk
notetype: Basic-02d89-e0e22
```

### Tags
```
bda::09_rl
```

## Front
When is the state transistion not deterministic? How do we have to adjust the action-value function?

## Back
\(V\left(s_{i}\right)=\max _{a_{i}} \mathrm{E}_{P}\left(r\left(s_{i}, a_{i}\right)+\gamma V\left(\tilde{s}_{i+1}\right)\right) \text { mit } \quad a_{i} \in A, \tilde{s}_{i+1} \sim P\left(s_{i}, a_{i}\right), \gamma \in[0,1]\)

<b>Example:</b>
State is dependent on vehicle and speed of vehicle influences the environment I'm in, however, the speed can not be influenced. That's why we sample from a distribution.
