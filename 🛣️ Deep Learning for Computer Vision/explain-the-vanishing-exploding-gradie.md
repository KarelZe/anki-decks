## Note
nid: 1655790028551
model: Basic-02d89-e0e22
tags: dl_cv::08_rnn
markdown: false

### Front
Explain the <b>vanishing / exploding gradient problem</b>.

### Back
Gradients will go towards
0 (vanishing gradients): when largest eigenvalue of \(W_{h h}<1\)
Inf (exploding gradients): when largest eigenvalue of \(W_{h h}>1\)

Problematic when unrolled to large length (typically \(n > 20\))
