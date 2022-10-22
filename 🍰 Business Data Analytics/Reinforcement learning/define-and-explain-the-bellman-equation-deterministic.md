# Note
```
guid: dQ|3*==7N|
notetype: Basic-02d89-e0e22
```

### Tags
```
bda::09_rl
```

## Front
Define and explain the <b>Bellman Equation (deterministic)</b>.

## Back
\[V\left(s_{0}\right)=\max _{a_{0}}\left(r\left(s_{0}, a_{0}\right)+\gamma V\left(s_{1}\right)\right) \quad \text { with } a_{0} \in A, s_{1}=T\left(s_{0}, a_{0}\right), \gamma \in[0,1]\]

with \(A\) being the action space. Calculates the optimal action in the current state iteratively until the end of the game.

<b>Explanation:</b>

<img src="paste-6fb81a999e5a81e2ee050b69f91d4578dc05000e.jpg">
