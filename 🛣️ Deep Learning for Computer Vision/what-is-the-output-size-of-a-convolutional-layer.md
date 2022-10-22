# Note
```
guid: v9Dsk4~s~!
notetype: Basic-02d89-e0e22
```

### Tags
```
dl_cv::04_deep_cnns_background
```

## Front
What is the output size of a <b>convolutional layer</b>?

## Back
Assume \(M\) channels at the input (3 for RGB) for Size \(D \times
D\). Take \(N\) filter kernels of size \(K \times K\) and convolve
with stride 1, and without any padding. <b>Output size:</b> \(((D-K
+2 \times padding) / stride) + 1\) <b>No. parameters:</b> \(N
\times M \times K \times K\)
