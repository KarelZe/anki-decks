## Note
nid: 1656320906484
model: Basic-02d89-e0e22
tags: dl_cv::misc
markdown: false

### Front
How does Sequence-toSequence Video-to-Text work? What is novel about it?

### Back
The S2VT approach performs video description using a sequence to
sequence model. A stacked LSTM first encodes the frames one by one,
taking as input the output of a CNN applied to each input frame’s
intensity values. Once all frames are read, the model generates a
sentence word by word. The encoding and decoding of the frame and
word representations are learned jointly from a parallel corpus. To
model the temporal aspects of activities typically shown in videos,
we also compute the optical flow between pairs of consecutive
frames. The flow images are also passed through a CNN and provided
as input to the LSTM. <b>Visualization:</b> <img src= 
"paste-15070d4dd24f4f0b66d89b5678205bd9820aeacd.jpg">
