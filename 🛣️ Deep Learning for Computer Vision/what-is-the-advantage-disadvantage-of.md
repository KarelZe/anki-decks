## Note
nid: 1651473953794
model: Basic-02d89
tags: 02_basics_nn_dlcv
markdown: false

### Front
What is the <b>advantage</b> / <b>disadvantage</b> of <b>Batch
Gradient Descent?</b>

### Back
<b>Pro:</b> Batch Gradient is guaranteed to converge to the global
minimum for a <b>convex error surfaces</b> and to a local minimum
for <b>non-convex surfaces</b>. <b>Con:</b> Full sum is expensive
when \(N\) the number of examples is large. Hard to hold in memory.
