## Note
nid: 1653666511015
model: Basic-02d89
tags: 05_neural_networks_bda
markdown: false

### Front
What is the idea behind <b>peephole connections</b> in
<b>LSTMs</b>?

### Back
In basic LSTM cells, gate only see short-term state and inputs. Provide more context by also looking at long-term states.

Therefore, \(c_{t-1}\) is provided as input to the forget gate and the input gate. The current \(c_{t}\) or \(c_{t-1}\) is added as input to the output gate.

<b>Visualization:</b>
<img src="lstm-cell-peephole.png">
