# Note
```
guid: At*Q{pxkM^
notetype: Basic-02d89-e0e22
```

### Tags
```
dl_cv::05_dl_architectures_2
```

## Front
What is the <b>problem</b> of a <b>naive inception module</b>?

## Back
Very expensive to compute due to high number of parameters (854M ops for 28x28x256 input).

Pooling layer also preserves feature depth, which means total depth after concatenation can only grow at every layer.
