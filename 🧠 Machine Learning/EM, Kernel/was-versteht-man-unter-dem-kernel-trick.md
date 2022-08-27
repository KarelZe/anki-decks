## Note
nid: 1610194005500
model: Basic-d7a3e-4ce08
tags: checklater, ml::07_kernel_methods, ultra
markdown: false

### Front
Was versteht man unter dem <b>Kernel Trick</b>?

### Back
<div>
  <div>
    <div>
      <div>
        <b>Eigene</b>
      </div>
      <ul>
        <li>Kernels können verwendet werden um Daten \(x\) in einen
        <em>infinite dimensional feature space</em> abzubilden.
        <li>Der <em>feature vector</em> muss dabei nie explizit
        repräsentiert sein. Es reicht aus, wenn wir das
        Kreuzprodukt bestimmen können.
        <li>Der <strong>kernel trick</strong> erlaubt, im
        originalen Feature Space zu operieren ohne dass
        Berechnungen der Koordinaten in einem höher-dimensionalen
        Raum notwendig sind.
        <li>Interessant, weil man dann eine mächtigere
        Repräsentation ggü. <strong>standard linear feature
        models</strong> erhält vgl. etwa SVM.
      </ul>
    </div>
  </div>
</div>
<div>
  <b>Erklärung Vorlesung</b>
</div>
<div>
  Ersetzen von einem Produkt zweier feature vectors durch eine
  Funktion.
</div>
