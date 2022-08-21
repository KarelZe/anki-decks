## Note
nid: 1629299324845
model: Basic-d7a3e
tags: 11_rnns, checklater
markdown: false

### Front
Explain the main components of a LSTM Cell.

### Back
<div>
  <ul>
    <li>LSTMs are a type of RNNs, that features a sophisticated
    <strong>forgetting</strong> and <strong>saving
    mechanism</strong>. To implement this, a LSTM is made up of
    four interacting <strong>layers</strong> and three
    <strong>gates</strong>.
    <li>Gates regulate what information is saved and removed from
    the cell state an LSTM cell. Gates implement a way to let
    information through. They are composed of a sigmoid neural net
    layer and pointwise multiplication operation (the hadamard
    product). If the output of a sigmoid layer is close to 0,
    hardly any information is passed through and vice versa if it’s
    close to 1.
    <li>Recall there are four gates:
      <ul>
        <li><strong>forget gate:</strong> whether to erase a cell
        <li><strong>input gate:</strong> how much to write to a
        cell
        <li><strong>gate gate:</strong> what to write to a cell
        (this is no gate in a closer sense?)
        <li><strong>output gate:</strong> how much to reveal a cell
      </ul>
  </ul>
</div>
