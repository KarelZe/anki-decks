## Note
nid: 1656181359719
model: Basic-02d89
tags: 09_rl, 09_rl_bda
markdown: false

### Front
What are the problems of approximating the Q-function? How can they be solved?

### Back
<b>Problem:</b> 
Approximation of Q-function (action-value function) using a nonlinear model was known to be unstable due to
<ul><li>the correlations present in the sequence of observations</li><li>the fact that small updates to \(Q\) may significantly change the policy and therefore change the data distribution</li><li>the correlations between the action-values \(Q\) and the target values</li></ul><b>Remedies:</b>
<ul><li>experience replay that randomizes over the data, thereby removing correlations in the observation sequence and smoothing over changes in the data distribution</li><li>iterative update that adjusts the action-values towards target values that are only periodically updated, thereby reducing correlations with the target</li></ul>
