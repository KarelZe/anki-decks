## Note
nid: 1652600160951
model: Basic-02d89-e0e22
tags: dl_cv::04_deep_cnns_background
markdown: false

### Front
What is the output size of a <b>convolutional layer</b>?

### Back
Assume \(M\) channels at the input (3 for RGB) for Size \(D \times
D\). Take \(N\) filter kernels of size \(K \times K\) and convolve
with stride 1, and without any padding. <b>Output size:</b> \(((D-K
+2 \times padding) / stride) + 1\) <b>No. parameters:</b> \(N
\times M \times K \times K\)
