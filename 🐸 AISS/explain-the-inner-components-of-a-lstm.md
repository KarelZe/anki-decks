## Note
nid: 1635925773981
model: Basic-d7a3e
tags: 03_evaluation, repeat
markdown: false

### Front
Explain the <b>inner components</b> of a <b>LSTM</b>.

### Back
<div>
  The LSTM is extended to a cell with the capability to store an
  internal state. The state is regulated by:
</div>
<ul>
  <li><strong>Input gate:</strong> Controls which values of the
  cell state get updated
  <li><strong>Output gate:</strong> Defines which part of the cell
  state will be used for the calculation of the output of the whole
  cell
  <li><strong>Forget gate:</strong> Decides which information is
  removed from the cell state
</ul>
<div><img src="1ahafyNt0Ph_J6Ed9_2hvdg.png"></div>
