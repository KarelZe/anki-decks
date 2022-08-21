## Note
nid: 1635149339855
model: Basic-d7a3e
tags: 02_forwards_futures, checklater
markdown: false

### Front
Wie lässt sich für einen ertragsbringenden Basiswert
<b>Long-Arbitrage</b> umsetzen? Wie <b>short-Arbitrage</b>?

### Back
<b>Long Arbitrage</b>:<div>Annahme \(f(0,T) > S(0)e^{rT}\):
<div>
</div><div>
</div><div>
<table>
<thead>
<tr>
<th></th>
<th><span style="font-weight: normal;">in \(T\)</span></th>
</tr>
</thead>
<tbody>
<tr>
<td>Forward short</td>
<td>\(f(0,T) - S(T)\)</td>
</tr>
<tr>
<td>Kreditfinanz. Kauf des Basiswerts</td>
<td>
<table><tbody><tr><td>\(-S(0)e^{rT} + S(T)\)</td>
</tr>
</tbody>
</table></td></tr></tbody></table>
</div><div>Damit folgt: \(f(0,T) - S(0)e^{rT}>0\)
</div><div></div><div><b>Short Arbitrage</b>:</div><div>
</div><div>Annahme \(f(0,T) < S(0)e^{rT}\):</div><div>
</div><div>
</div></div>
<table>
<thead>
<tr>
<th></th>
<th><span style="font-weight: normal;">in </span>\(T\)</th>
</tr>
</thead>
<tbody>
<tr>
<td>Forward long</td><td>\(S(T) -f(0,T)\)</td>
</tr>
<tr>
<td>Leerverkauf des Basiswerts + risikolose Anlage
</td>
<td>
<table><tbody><tr><td>\(-S(T) + S(0)e^{rT}\)</td></tr></tbody></table>
</td></tr></tbody></table>Damit folgt: \(S(0)e^{rT} - f(0,T) > 0\)
