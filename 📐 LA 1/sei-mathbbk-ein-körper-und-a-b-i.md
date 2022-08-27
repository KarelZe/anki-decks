## Note
nid: 1580539366596
model: LaTeX-deb4a
tags: Eigene
markdown: false

### Front
Sei $\mathbb{K}$ ein Körper und $A, B \in \mathbb{K}^{n \times n}$ quadratische Matrizen. Weiter bezeichne
$$
\operatorname{tr}: \mathbb{K}^{n \times n} \rightarrow \mathbb{K},\left(x_{i j}\right) \mapsto \sum_{i=1}^{n} x_{i i}
$$
die Spurabbildung. <div>
</div><div>Zeigen Sie, dass $\operatorname{tr}(A \cdot B)=\operatorname{tr}(B \cdot A)$ gilt.</div>

### Back
Es gilt:<div>$$\operatorname{tr}(A B)=\sum_{i}<span>^{n}</span><span> \sum_{i}</span><span>^{n}</span><span> a_{i j} b_{j i}</span><span>=\sum_{i}</span><span>^{n}</span><span> \sum_{i}</span><span>^{n}</span><span> b_{j i} a_{i j}$$.</span></div><div>
</div><div>Jedes Paar von Buchstaben kann benutzt werden, um die Indizes einer Summe zu repräsentieren. Daher ist ein Umschreiben nach:</div><div>$\sum_{r=1}^{n} \sum_{s=1}^{n} b_{r s} a_{s r}$
</div><div>möglich.</div><div>
</div><div>Dies entspricht genau der Spur $\operatorname{tr}(B A)$.</div>
