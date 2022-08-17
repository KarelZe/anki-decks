## Note
nid: 1656171924371
model: Basic-02d89
tags: 09_rl, 09_rl_bda
markdown: false

### Front
What is the <b>idea</b> of the <b>prioritized replay buffer</b>?

### Back
The idea is to train on data, that is surprising and doesn't necessarily come in order. Hence, use a prioritized replay buffer.

To obtain the priority for the buffer, the priority is made proportional to the loss for this particular example in the Bellman update. New samples added to the buffer are assigned a maximum value of priority to be sure they will be sampled soon.
