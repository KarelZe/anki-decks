## Note
nid: 1635751146749
model: Basic-d7a3e-4ce08
tags: derivate::02_forwards_futures
markdown: false

### Front
Leiten Sie her, welcher Zusammenhang zwischen Forward und Future bei konstanten Zinsen gilt.

### Back
Risikolose Mittelanlage \(F^0\) bis \(T\) und Durchführung der Futures Strategie:<div>
</div>
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-0pky{border-color:inherit;text-align:left;vertical-align:top}
.tg .tg-0lax{text-align:left;vertical-align:top}
</style>
<table class="tg">
<thead>
<tr>
<th class="tg-0pky">Tag</th>
<th class="tg-0pky">0</th>
<th class="tg-0pky">\(n\)</th>
</tr>
</thead>
<tbody>
<tr>
<td class="tg-0pky">Mittelanlage</td><td class="tg-0pky">\( -F^0\)</td>
<td class="tg-0pky">\( F^0 e^{rn}\)</td>
</tr>
<tr>
<td class="tg-0pky">Future Strategie</td>
<td class="tg-0pky">-</td>
<td class="tg-0pky">\((S(n) - F^0 )e^{rn}\)</td>
</tr>
<tr>
<td class="tg-0pky">Portfolio</td>
<td class="tg-0pky">\( -F^0\)
</td>
<td class="tg-0pky">\(S(n) e^{rn}\)</td>
</tr>
</tbody>
</table>
<div>
</div><div>Risikolose Mittelanlage von \(f^0\) bis \(T\) und \(e^{nr}\) Forwards long:</div><div>
</div><div>
</div>
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-0pky{border-color:inherit;text-align:left;vertical-align:top}
.tg .tg-0lax{text-align:left;vertical-align:top}
</style>
<table class="tg">
<thead>
<tr>
<th class="tg-0pky">Tag</th>
<th class="tg-0pky">0</th>
<th class="tg-0pky">\(n\)</th>
</tr>
</thead>
<tbody>
<tr>
<td class="tg-0pky">Mittelanlage</td>
<td class="tg-0pky">\(-f^0\)</td>
<td class="tg-0pky">\( f^0 e^{rn}\)
</td></tr><tr><td class="tg-0pky">\( e^{rn}\) Forwards long</td>
<td class="tg-0pky">-</td>
<td class="tg-0pky">\((S(n) - f^0) e^{rn}\)</td>
</tr>
<tr>
<td class="tg-0pky">Portfolio</td>
<td class="tg-0pky">\(-f^0\)</td>
<td class="tg-0pky">\(S(n) e^{rn}\)</td>
</tr>
</tbody>
</table>
<div>Aus <b>No-Arbitrage</b> / <b>Gesetz des einen Preis</b> folgt \(F^0 = f^0\).</div>
