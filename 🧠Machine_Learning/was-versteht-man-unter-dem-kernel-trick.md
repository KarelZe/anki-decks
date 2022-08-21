## Note
nid: 1610194005500
model: Basic-d7a3e
tags: 07_kernel_methods, checklater, ultra
markdown: false

### Front
Was versteht man unter dem <b>Kernel Trick</b>?

### Back
<div><div>
<div><div><b>Eigene</b></div><ul>
<li>Kernels können verwendet werden um Daten \(x\) in einen <em>infinite dimensional feature space</em> abzubilden.</li>
<li>Der <em>feature vector</em> muss dabei nie explizit repräsentiert sein. Es reicht aus, wenn wir das Kreuzprodukt bestimmen können.</li>
<li>Der <strong>kernel trick</strong>
 erlaubt, im originalen Feature Space zu operieren ohne dass 
Berechnungen der Koordinaten in einem höher-dimensionalen Raum 
notwendig sind.</li>
<li>Interessant, weil man dann eine mächtigere Repräsentation ggü. <strong>standard linear feature models</strong> erhält vgl. etwa SVM.</li>
</ul>
</div></div></div><div>
</div><div><b>Erklärung Vorlesung</b></div><div>
</div><div>Ersetzen von einem Produkt zweier feature vectors durch eine Funktion.</div>
