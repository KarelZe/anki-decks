# Note
```
guid: p#a=uy:?#p
notetype: Basic-b122e-20a86
```

### Tags
```
03_collaborative_filtering
```

## Front
Welcher Ansatz wird zur Evaluation von <b>Collaborative Filtering-Modellen</b> benutzt?

## Back
<p>Eine Confusion-Matrix:</p>
<table border="1">
<thead>
<tr>
<th style="text-align: left;"></th>
<th style="text-align: center;">vorausgesagt gut</th>
<th style="text-align: center;">vorausgesagt schlecht</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: left;">ist gut</td>
<td style="text-align: center;">korrekt gezeigt</td>
<td style="text-align: center;"><span class="math inline">\(\beta:\)</span> nicht gezeigte gute Empfehlung</td>
</tr>
<tr>
<td style="text-align: left;">ist schlecht</td>
<td style="text-align: center;"><span class="math inline">\(\alpha:\)</span> schlechte Empfehlung</td>
<td style="text-align: center;">korrekt versteckt</td>
</tr>
</tbody>
</table>
<p><span class="math inline">\(L = w_{1} n_{\alpha}+w_{2} n_{\beta}\)</span> <span class="math inline">\(=\)</span> <span class="math inline">\(L=\left(w_{1} \alpha+w_{2} \beta\right) n\),</span> </p><p><span class="math inline">\(w_{1}\)</span> Kosten für Lesen einer schlechten Empfehlung, </p><p><span class="math inline">\(w_{2}\)</span> Kosten für Übersehen einer guten Empfehlung,</p>
<p><span class="math inline">\(\alpha\)</span> = Fehler 1. Art und <span class="math inline">\(\beta\)</span> = Fehler 2. Art.</p>
