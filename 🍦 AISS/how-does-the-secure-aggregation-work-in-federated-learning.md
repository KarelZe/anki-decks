# Note
```
guid: PuNj!w2P[w
notetype: Basic-02d89-e0e22
```

### Tags
```
06_systemwide_learning
```

## Front
How does the secure aggregation work in federated learning?

## Back
<b>Goal:</b> Compute a multiparty sum where no party reveals its
update, even to the aggregator <b>Secure aggregation protocol</b>:
<ul>
  <li>Operate on high dimensional vectors
  <li>Communication efficient
  <li>Robust to dropout of users (Users leaving the system)
</ul>Based on <b>Shamir's t-out-of-n secret sharing</b>:
<ul>
  <li>Secret can be split into n shares with any t shares can
  reconstruct s, but any set of at most t-1 shares gives no
  information about s.
</ul><b>Visualization</b>: <img src="59070685.png">
