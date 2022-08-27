## Note
nid: 1610822107190
model: Basic-d7a3e-4ce08
tags: 04_koheraenz, 11_para_block_prozess
markdown: false

### Front
Was versteht man unter einer <b>koheränten Sicht</b> auf den
Speicher hinsichtlich <b>Cache-Koheränz</b>?

### Back
Ein Speichersystem ist koheränt, wenn ein Lesezugriff eines
Prozessors P auf eine Speicherseite X, der auf einen Schreibzugriff
eines anderen Prozessors auf die Stelle X folgt, den geschriebenen
Wert liefert, falls der Lese- und Schreibzugriff zeitlich
ausreichend getrennt erfolgen und in der Zwischenzeit keine anderen
Schreibzugriffe auf die Stelle X erfolgen.<img src="32447141.png">
<div>
  Bei einem Uni-Prozessor: Ein Load muss immer den letzten Wert in
  der Threadordnung der Schreiboperation auf dieselbe Adresse
  zurückliefern.
</div>
