## Note
nid: 1629295461878
model: Basic-d7a3e
tags: 11_rnns
markdown: false

### Front
Explain what is characteristic about <b>AlexNet</b>.

### Back
[227x227x3] INPUT (images of size 227 x 227) [55x55x96] CONV1 : 96
11x11 filters at stride 4, pad 0 [27x27x96] MAX POOL1 : 3x3 filters
at stride 2 [27x27x96] NORM1 : Normalization layer [27x27x256]
CONV2 : 256 5x5 filters at stride 1, pad 2 [13x13x256] MAX POOL2 :
3x3 filters at stride 2 [13x13x256] NORM2 : Normalization layer
[13x13x384] CONV3 : 384 3x3 filters at stride 1, pad 1 [13x13x384]
CONV4 : 384 3x3 filters at stride 1, pad 1 [13x13x256] CONV5 : 256
3x3 filters at stride 1, pad 1 [6x6x256] MAX POOL3 : 3x3 filters at
stride 2 [4096] FC6 : 4096 neurons [4096] FC7 : 4096 neurons [1000]
FC8 : 1000 neurons (class scores)
<div><img src=
"paste-01d904854611ff65e1ec4aa224c552e774baaf73.jpg"></div>
