# Note
```
guid: F9EX}}^C9&
notetype: Basic-02d89-e0e22
```

### Tags
```
dl_cv::08_rnn
```

## Front
Name all gates in a <b>LSTM cell</b> and explain their job. How do they calculate their output?

## Back
<b>Forget gate:</b>
Allows to "reset" or "keep" cell state information
Multiplies with previous cell state \(C_{t-1}\)
Looks at previous hidden state \(h_{t-1}\) and new input \(x_{t}\)
Amount of reset normalized using a sigmoid \(\sigma\)
<b>
Input and new cell state:</b>
Considers what to include from the new input
Looks at previous hidden state \(h_{t-1}\) and new input \(x_{t}\)
New cell state is in the \(-1\) to \(+1\) range (tanh)
Also looks at previous hidden state \(h_{t-1}\) and new input \(x_{t}\)
<b>
Update cell state:</b>
Considers how much to forget the old cell state \(C_{t-1}\)
Then adds modulated information from the new input
Creates new cell state \(C_{t}\) carried forward to next iteration
<b>
Output gate:</b>
Output gate, considers how much to pass on to the new hidden state
Looks at previous hidden state \(h_{t-1}\) and new input \(x_{t}\)
Modulates the new cell state \(C_{t}\) to produce new hidden state \(h_{t}\)
The output \(y_{t}=W_{h y} h_{t}\) as before

<b>Cell state:</b>
Cell state is a through line with minor interactions

<img src="paste-002c367953bacaceb5887a44c889a4edc06d1256.jpg">
<img src="paste-dacc329823c0757fa5e4fd440033287c7ca7b292.jpg">
<img src="paste-8174f0a8f08ffd8545d5e5b7196774a9477e1767.jpg">
<img src="paste-a2d06e47d00cc59a9d90d49e193d6e91393cc7e0.jpg">
