## Note
nid: 1656181707198
model: Basic-02d89-e0e22
tags: bda::09_rl
markdown: false

### Front
Why are <b>correlations</b> in <b>observations</b> problematic in
<b>reinforcement learning</b>?

### Back
<div>
  <ul>
    <li>Samples are not independent. Even if we accumulate a large
    batch of data samples, they will all be very close to each
    other, as they will belong to the same episode.
    <li>Distribution of our training data won't be identical to
    samples provided by the optimal policy that we want to learn.
    Data that we have will be a result of some other policy (our
    current policy, random, or both in the case of epsilon-greedy),
    but we don't want to learn how to play randomly: we want an
    optimal policy with the best reward.
  </ul>
</div>
