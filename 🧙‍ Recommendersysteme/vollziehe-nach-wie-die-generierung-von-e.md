## Note
nid: 1588675777897
model: Basic-b122e-20a86
tags: 03_collaborative_filtering
markdown: false

### Front
Vollziehe nach wie die Generierung von Empfehlung mittels <b>Collaborative Filtering</b> funktioniert.

### Back
<p>Sei Rater: <span class="math inline">\(k, l \in 1, \ldots, m\)</span> Sei Msgs: <span class="math inline">\(m \in 1, \ldots, n\)</span> </p><p>Sei Matrix: <span class="math inline">\(X: m \times n\)</span> Matrix</p>
<table border="1">
<thead>
<tr>
<th style="text-align: center;">msg</th>
<th style="text-align: center;">Ken</th>
<th style="text-align: center;">Lee</th>
<th style="text-align: center;">Meg</th>
<th style="text-align: center;">Nan</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: center;">1</td>
<td style="text-align: center;">1</td>
<td style="text-align: center;">4</td>
<td style="text-align: center;">2</td>
<td style="text-align: center;">2</td>
</tr>
<tr>
<td style="text-align: center;">2</td>
<td style="text-align: center;">5</td>
<td style="text-align: center;">2</td>
<td style="text-align: center;">4</td>
<td style="text-align: center;">4</td>
</tr>
<tr>
<td style="text-align: center;">3</td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
<td style="text-align: center;">3</td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;">4</td>
<td style="text-align: center;">2</td>
<td style="text-align: center;">5</td>
<td style="text-align: center;"></td>
<td style="text-align: center;">5</td>
</tr>
<tr>
<td style="text-align: center;">5</td>
<td style="text-align: center;">4</td>
<td style="text-align: center;">1</td>
<td style="text-align: center;"></td>
<td style="text-align: center;">1</td>
</tr>
<tr>
<td style="text-align: center;">6</td>
<td style="text-align: center;"><span class="math inline">\(?\)</span></td>
<td style="text-align: center;">2</td>
<td style="text-align: center;">5</td>
<td style="text-align: center;"><span class="math inline">\(?\)</span></td>
</tr>
</tbody>
</table>
<p>

In der Matrix <span class="math inline">\(X\)</span> bezeichnet ein ?, die Nachricht, wofür eine Vorhersage gemacht werden soll.</p><p>

Rater: <span class="math inline">\(k, l \in 1, \ldots, m\)</span> [Spalten] </p><p>Messages: <span class="math inline">\(p \in 1, \ldots, n[\mathrm{Zeilen}]\)</span></p><p>
Rating Matrix: <span class="math inline">\(X, n \times m\)</span> Matrix

</p><p>
Wir partitionieren <span class="math inline">\(X\)</span> in Spalten:

<span class="math inline">\(X=\left[s_{1}\left|s_{2}\right| \ldots | s_{m}\right]\)</span> Spalten!</p><p>Wir partitionieren <span class="math inline">\(X\)</span> in Zeilen:<span class="math inline">\(X=\left[\begin{array}{c}z_{1} \\ z_{2} \\ \vdots \\ z_{n}\end{array}\right]\)</span> Zeilen!
</p><p>
<strong>
</strong></p><p><strong>Schritt1: Ähnlichkeit zwischen Ratern berechnen:</strong>

Mittleres Rating von Rater <span class="math inline">\(k\)</span> <span class="math inline">\(\bar{x}_{k}=\frac{1}{n} \sum s_{k}\)</span> </p><p>Korrelation von Rater <span class="math inline">\(k\)</span> und Rater <span class="math inline">\(l\)</span> <span class="math inline">\(r_{k l}=\frac{c o v\left(s_{k}, s_{l}\right)}{\sigma_{k} \sigma_{l}}=\frac{\sum_{i}\left(x_{i, k}-\bar{x}_{k}\right)\left(x_{i, l}-\bar{x}_{l}\right)}{\sqrt{\sum_{i}\left(x_{i, k}-\bar{x}_{k}\right)^{2}} \sqrt{\sum_{i}\left(x_{i, l}-\bar{x}_{l}\right)^{2}}}\)</span></p><p>

<strong>Schritt 2: Voraussage für das Rating von User <span class="math inline">\(k\)</span> für die Message <span class="math inline">\(p\)</span></strong>

Voraussage für das Rating von User <span class="math inline">\(k\)</span> für Message <span class="math inline">\(p\)</span> <span class="math display">\[x_{p, k}=\bar{x}_{k}+\frac{\sum_{j}\left(x_{p, j}-\bar{x}_{j}\right) r_{k, j}}{\sum_{j}\left|r_{k, j}\right|}\]</span> mit <span class="math inline">\(j \in\)</span> raters (also alle User, die die Message <span class="math inline">\(p\)</span> bereits geratet haben)</p>
