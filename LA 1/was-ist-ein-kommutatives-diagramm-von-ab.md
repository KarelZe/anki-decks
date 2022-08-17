## Note
nid: 1580142982702
model: LaTeX
tags: Logik
markdown: false

### Front
Was ist ein kommutatives Diagramm von Abbildungen?

### Back
<pre><span style="font-family: Arial; background-color: rgb(255, 
 255, 255);">\begin{tikzpicture}</span>
</pre>
<pre>  \matrix (m)
    [
      matrix of math nodes,
      row sep    = 3em,
      column sep = 4em
    ]
    {
      M              & N \\
      O &             \\
    };
  \path
    (m-1-1) edge [->] node [left] {$f$} (m-2-1)
    (m-1-1.east |- m-1-2)
      edge [->] node [above] {$g \circ f$} (m-1-2)</pre>
<pre>    (m-2-1.east) edge [->] node [below] {$g$} (m-1-2);</pre>
<pre>\end{tikzpicture}</pre>
