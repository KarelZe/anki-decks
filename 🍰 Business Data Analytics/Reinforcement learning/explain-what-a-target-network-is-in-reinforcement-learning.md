# Note
```
guid: EXe04o/RfO
notetype: Basic-02d89-e0e22
```

### Tags
```
bda::09_rl
```

## Front
Explain what a <b>target network</b> is in <b>reinforcement
learning</b>.

## Back
To make training more stable, there is a trick, called target
network, by which we keep a copy of our network and use it for the
\(Q\left(s^{\prime}, a^{\prime}\right)\) value in the Bellman
equation. This network is synchronized with our main network only
periodically. <img src="paste-bb6b6d2b36d6491bbc3486c97029f9f0778e097a.jpg">
