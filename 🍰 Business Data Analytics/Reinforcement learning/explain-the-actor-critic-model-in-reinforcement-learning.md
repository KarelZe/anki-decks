# Note
```
guid: w)Ao/=_4!g
notetype: Basic-02d89-e0e22
```

### Tags
```
bda::09_rl
```

## Front
Explain the <b>actor-critic model</b> in <b>reinforcement
learning</b>.

## Back
<img src="paste-2b88049417578b2c0f51c07bc0c43f8d0cbe423e.jpg"> In a
simple term, Actor-Critic is a Temporal Difference(TD) version of
Policy gradient. It has two networks: Actor and Critic. The actor
decided which action should be taken and critic inform the actor
how good was the action and how it should adjust. The learning of
the actor is based on policy gradient approach. In comparison,
critics evaluate the action produced by the actor by computing the
value function. <b>intuition:</b> There are two parties, the actor
and the critic, similar to a GAN.
