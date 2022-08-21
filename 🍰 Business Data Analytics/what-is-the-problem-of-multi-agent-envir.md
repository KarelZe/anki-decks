## Note
nid: 1656176415516
model: Basic-02d89
tags: 09_rl, 09_rl_bda
markdown: false

### Front
What is the problem of <b>multi-agent environments</b>? How can it be solved?

### Back
<div>
  <ul>
    <li>Most of the successes of RL have been in single agent
    domains, where modelling or predicting the behavior of other
    actors in the environment is largely unnecessary. However, in
    multi-agent environments simple gradient descent approaches are
    no longer stable as results do not only depend on the
    individual policy.
    <li>This can be overcome by providing additional information to
    the critic on competitor behavior in an actor-critic model,
    while the actor (who optimizes the policy) only uses locally
    available information.
  </ul>
</div><img src=
"paste-26d2f31a424e58fc26bad74d6a234258b92f1805.jpg">
