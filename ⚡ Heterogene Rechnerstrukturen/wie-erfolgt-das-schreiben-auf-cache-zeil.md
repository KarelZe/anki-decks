## Note
nid: 1610825404921
model: Basic-d7a3e-4ce08
tags: 04_koheraenz, 11_para_block_prozess
markdown: false

### Front
Wie erfolgt das Schreiben auf Cache-Zeilen mit mehreren Wörtern
beim <b>Write-Invalidate Protokoll</b>? Wie beim
<b>Write-Update-Protokoll</b>?

### Back
<b>Write-Invalidate-Protokoll:</b>
<div>
  Die erste Schreiboperation auf ein Wort eines Cache-Blocks
  erfordert eine Invalidierung.
</div>
<div>
  <b>Write-Update-Protokoll:</b>
</div>
<div>
  Arbeitet auf Wort-Ebene. Für jedes Wort in einem Block, das
  geschrieben wurde, ist ein Write-Broadcast nötig.
</div>
