## Note
nid: 1588675281760
model: Basic-b122e
tags: 03_collaborative_filtering
markdown: false

### Front
Welcher Ansatz wird zur Evaluation von <b>Collaborative
Filtering-Modellen</b> benutzt?

### Back
<p>Eine Confusion-Matrix:
<table border="1">
  <thead>
    <tr>
      <th style="text-align: left;">
      <th style="text-align: center;">vorausgesagt gut
      <th style="text-align: center;">vorausgesagt schlecht
  <tbody>
    <tr>
      <td style="text-align: left;">ist gut
      <td style="text-align: center;">korrekt gezeigt
      <td style="text-align: center;"><span class="math
      inline">\(\beta:\)</span> nicht gezeigte gute Empfehlung
    <tr>
      <td style="text-align: left;">ist schlecht
      <td style="text-align: center;"><span class="math
      inline">\(\alpha:\)</span> schlechte Empfehlung
      <td style="text-align: center;">korrekt versteckt
</table>
<p><span class="math inline">\(L = w_{1} n_{\alpha}+w_{2}
n_{\beta}\)</span> <span class="math inline">\(=\)</span>
<span class="math inline">\(L=\left(w_{1} \alpha+w_{2} \beta\right)
n\),</span>
<p><span class="math inline">\(w_{1}\)</span> Kosten für Lesen
einer schlechten Empfehlung,
<p><span class="math inline">\(w_{2}\)</span> Kosten für Übersehen
einer guten Empfehlung,
<p><span class="math inline">\(\alpha\)</span> = Fehler 1. Art und
<span class="math inline">\(\beta\)</span> = Fehler 2. Art.
