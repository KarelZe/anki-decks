## Note
nid: 1652108477980
model: Basic-02d89
tags: 03_nn_basics_dlcv
markdown: false

### Front
Explain <b>drop-out</b>.

### Back
<b>Training:</b> in each iteration, ignore (zero out) a random fraction \(p\) of the nodes (and corresponding activations).
<b>Testing:</b> Deactivate drop-out. Alternatively multiply outgoing weights by \(p\) at test-time.

<b>Visualization:</b>
<img src="paste-7fe4fa38462bdf755b0be2cd5d2321a6078a0e6b.jpg">
<img src="paste-c26a4814220056397125125da64491c80f17e8d1.jpg">
