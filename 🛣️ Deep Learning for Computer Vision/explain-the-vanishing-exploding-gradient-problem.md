# Note
```
guid: fzct=<`el~
notetype: Basic-02d89-e0e22
```

### Tags
```
dl_cv::08_rnn
```

## Front
Explain the <b>vanishing / exploding gradient problem</b>.

## Back
Gradients will go towards
0 (vanishing gradients): when largest eigenvalue of \(W_{h h}<1\)
Inf (exploding gradients): when largest eigenvalue of \(W_{h h}>1\)

Problematic when unrolled to large length (typically \(n > 20\))
