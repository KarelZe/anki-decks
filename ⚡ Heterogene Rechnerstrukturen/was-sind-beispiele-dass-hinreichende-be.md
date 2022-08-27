## Note
nid: 1611769954743
model: Basic-d7a3e-4ce08
tags: 04_koheraenz, 11_para_block_prozess
markdown: false

### Front
Was sind Beispiele, dass <b>hinreichende Bedingungen</b> für
<b>Koheränz</b> nicht erfüllt werden?

### Back
<div>
  Die Frage, wann ein geschriebener Wert gesehen wird, ist wichtig:
</div>
<div>
  Man kann nicht fordern, dass ein Lesezugriff auf eine Stelle X
  sofort den Wert liefert, der von einem Schreibzugriff auf X eines
  anderen Prozessors stammt.
</div>
<div>
  <b>Beispiel:</b> Die Schreiboperation eines Prozessors auf die
  Stelle X erfolgt kurz vor dem Lesezugriff eines anderen
  Prozessors auf diese Stelle, dann kann nicht gesichert werden,
  dass die Leseoperation den richtigen Wert erhält, da
  möglicherweise die zu schreibenden Daten den Prozessor noch nicht
  verlassen haben.
</div>
<div>
  Beispielhaft wird bei einer RISK-Pipeline ein <b>store buffer</b>
  verwendet, der dem Datencache vorgelagert ist.
</div>
<div><img src="25751457.png"></div>
<div>
  Im Store Buffer werden Schreiboperationen abgelegt bis der Cache
  aktualisiert werden kann. Es dauert 1-2 Takte bis Cache
  aktualisiert ist.
</div>
<div>
  Nun kann es passieren, dass bei Leseoperationen passieren, dass
  Wert aus Store Buffer genommen wird. Die Schreiboperation aber
  erst später erfolgt.
</div>
<div>
  Die Programmordnung entspricht damit nicht mehr der, wie sie der
  Prozessor sieht.
</div>
