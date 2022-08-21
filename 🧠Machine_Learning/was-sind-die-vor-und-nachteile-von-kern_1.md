## Note
nid: 1628926276865
model: Basic-d7a3e
tags: 07_kernel_methods, ultra
markdown: false

### Front
Was sind die <b>Vor- und Nachteile</b> von <b>Kernel Ridge
Regression</b>?

### Back
<div>
  <div>
    Die Lösung für Kernel Ridge Regression ist gegeben durch:
  </div>
  <div>
    \(f^{*}(\boldsymbol{x})=\boldsymbol{k}(\boldsymbol{x})^{T}(\boldsymbol{K}+\lambda
    \boldsymbol{I})^{-1} \boldsymbol{y})\)
  </div>
  <div>
    <strong>Vorteile</strong>
  </div>
  <ul>
    <li>Keine Auswertung der Feature Vektoren erforderlich
    <li>Lediglich der Skalarprodukte der Inputvektoren
    (ausgewertetet durch den Kernel)
    <li>Nur wenige Hyperparameter notwendig
  </ul>
  <div>
    <strong>Nachteile</strong>
  </div>
  <ul>
    <li>Erfordert die Invertierung einer \(N \times N\) Matrix, was
    teuer ist \(\mathcal{O}(n^{2.376})\)
    <li>Alle Samples müssen in einer Kernel-basierten Methode
    gespeichert werden, was sich aus Größe der Kernel-Matrix
    begründen lässt.
  </ul>
</div>
