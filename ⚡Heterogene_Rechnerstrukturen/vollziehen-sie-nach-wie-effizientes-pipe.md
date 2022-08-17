## Note
nid: 1605038554217
model: Basic-b122e
tags: 01_einfuehrung, 01_einfuehrung_rs, 01_vorlesung, 06_para_maschinenbefehl
markdown: false

### Front
<p>Vollziehen Sie nach wie effizientes Pipelining eines
Maschinenbefehls bei <b>RISC</b> funktioniert.

### Back
<p><img src="1du6H7cZxJTBJp7ZjMhv.png" style="width: 366px;"></p><dl><dt>Befehlscode laden (IF, Instruction Fetch) In der Befehlsbereitstellungsphase wird der Befehl, der durch den 
Befehlszähler adressiert ist, aus dem Arbeitsspeicher geladen. Der 
Befehlszähler wird anschließend hochgezählt.</dt>
<dt>
</dt><dt>Instruktion dekodieren und Laden der Daten (ID, Instruction Decoding) In der Dekodier- und Ladephase wird der geladene Befehl dekodiert 
(1. Takthälfte) und die notwendigen Daten aus dem Arbeitsspeicher und 
dem Registersatz geladen (2. Takthälfte).</dt>
<dt>
</dt><dt>Befehl ausführen (EX, Execution) In der Ausführungsphase wird der dekodierte Befehl ausgeführt. Das Ergebnis wird durch den  Pipeline-latch gepuffert.</dt>
<dt>
</dt><dt>Ergebnisse zurückgeben (WB, Write Back) In der Resultatspeicherphase wird das Ergebnis in den Arbeitsspeicher oder in den Registersatz zurückgeschrieben.</dt></dl>
