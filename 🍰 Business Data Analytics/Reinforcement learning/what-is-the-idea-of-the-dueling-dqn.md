# Note
```
guid: l&FhrTP3[5
notetype: Basic-02d89-e0e22
```

### Tags
```
bda::09_rl
```

## Front
What is the <b>idea </b>of the <b>Dueling DQN</b>?

## Back
The Q-values \(Q(s,a)\) that the network is traing to approximate is divided into quantities.
The value of the state, \(V(s)\) and th eadvantage of actions in this state, \(A(s,a)\) such that \(Q(s,a)=V(s)+A(s,a)\).
To achieve stable training, the mean value of the Advantage is constrained to 0.

<b>Architecture:</b>
Like the standard DQN architecture, we have convolutional layers to process game-play frames. From there, we split the network into two separate streams, one for estimating the state-value and the other for estimating state-dependent action advantages. After the two streams, the last module of the network combines the state-value and advantage outputs.

<img src="paste-781e111af0dcf2beaf9f2c503c989eb1f42a625e.jpg">
