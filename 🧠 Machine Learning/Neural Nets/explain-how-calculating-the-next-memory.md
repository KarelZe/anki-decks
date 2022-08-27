## Note
nid: 1629301334150
model: Basic-d7a3e-4ce08
tags: checklater, ml::11_rnns
markdown: false

### Front
Explain how calculating the next memory state \(c_t\) of a LSTM cell works.

### Back
<div>
  <b>Forget gate</b> \(f\) (whether to erase cell)
</div>
<div>
  \(\boldsymbol{f}_{t}=\sigma\left(\boldsymbol{W}_{f}\left[\begin{array}{c}\boldsymbol{h}_{t-1}
  \\ \boldsymbol{x}_{t}\end{array}\right]\right)\)
</div>
<div>
  <b>Input gate</b> \(i\) (whether to write to cell)
</div>
<div>
  \(i_{t}=\sigma\left(\begin{array}{c}\boldsymbol{W}_{i} &
  {\left[\begin{array}{c}\boldsymbol{h}_{t-1} \\
  \boldsymbol{x}_{t}\end{array}\right]}\end{array}\right)\)
</div>
<div>
  <b>Gate gate</b> \(g\) (how much to write to cell)
</div>
<div>
  \(\boldsymbol{g}_{t}=\tanh
  \left(\boldsymbol{W}_{g}\left[\begin{array}{c}\boldsymbol{h}_{t-1}
  \\ \boldsymbol{x}_{t}\end{array}\right]\right)\)
</div><b>Output gate</b> \(o\) (how much to reveal to cell)
<div>
  \(\boldsymbol{o}_{t}=\sigma\left(\boldsymbol{W}_{o}\left[\begin{array}{c}\boldsymbol{h}_{t-1}
  \\ \boldsymbol{x}_{t}\end{array}\right]\right)\)
</div>
<div>
  Next memory state
</div>
<div>
  \(\boldsymbol{c}_{t}=\boldsymbol{f}_{t} \circ
  \boldsymbol{c}_{t-1}+\boldsymbol{i}_{t} \circ \boldsymbol{g}_{t},
  \quad \boldsymbol{h}_{t}=\boldsymbol{o}_{t} \circ \tanh
  \left(\boldsymbol{c}_{t}\right)\)
</div>
