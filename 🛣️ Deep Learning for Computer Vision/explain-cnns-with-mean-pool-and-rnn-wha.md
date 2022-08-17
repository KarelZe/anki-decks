## Note
nid: 1656320435353
model: Basic-02d89
tags: 
markdown: false

### Front
Explain <b>CNNs</b> with <b>Mean Pool</b> and <b>RNN</b>. What was novel about this approach?

### Back
Translate videos directly to sentences using
a unified deep neural network with both convolutional and recurrent structure.

Utilize
a Long-Short Term Memory (LSTM) to
model sequence dynamics, but connect it directly to
a deep convolutional neural network to process incoming video frames, avoiding supervised intermediate representations altogether. This model is similar to a image-to-text model, but we adapt it for
video sequences.

<b>Visualization:</b>
<img src="paste-e6bc1dd1fd964c159d317650b68342c981f76519.jpg">
