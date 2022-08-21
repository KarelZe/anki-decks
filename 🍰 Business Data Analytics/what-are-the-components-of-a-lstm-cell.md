## Note
nid: 1653670781783
model: Basic-02d89
tags: 05_neural_networks_bda
markdown: false

### Front
What are the <b>components </b>of a <b>LSTM cell</b>.

### Back
\(g_t\) as in simple RNN cell looks at previous input and state,
but partially stored long-term memory. <b>Forget Gate:</b> controls
which part of long-term memory should be erased. <b>Input (update)
Gate:</b> which parts hould be added to long-term memory. <b>Output
gate:</b> which parts of long-term memory should be read and output
in current time step. <b>Formulas:</b> \[\begin{aligned} u_{t}
&=\sigma\left(W_{x i}^{\mathrm{T}} \cdot x_{t}+W_{h
i}^{\mathrm{T}} \cdot h_{t-1}+b_{i}\right) \\ f_{t}
&=\sigma\left(W_{x f}^{\mathrm{T}} \cdot x_{t}+W_{h
f}^{\mathrm{T}} \cdot h_{t-1}+b_{f}\right) \\ o_{t}
&=\sigma\left(W_{x o}^{\mathrm{T}} \cdot x_{t}+W_{h
o}^{\mathrm{T}} \cdot h_{t-1}+b_{o}\right) \\ g_{t} &=\tanh
\left(W_{x g}^{\mathrm{T}} \cdot x_{t}+W_{h g}^{\mathrm{T}} \cdot
h_{t-1}+b_{g}\right) \\ c_{t} &=f_{t} \otimes c_{t-1}+u_{t}
\otimes g_{t} \\ y_{t} &=h_{t}=o_{t} \otimes \tanh
\left(c_{t}\right) \end{aligned}\] <b>Visualization:</b> <img src= 
"paste-8988fb076cf22753afa5423fc11dd9c9a244760b.png">
