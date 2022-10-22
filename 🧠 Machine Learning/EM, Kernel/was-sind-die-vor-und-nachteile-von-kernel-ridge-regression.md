# Note
```
guid: s7~-x[_yT]
notetype: Basic-d7a3e-4ce08
```

### Tags
```
ml::07_kernel_methods
ultra
```

## Front
Was sind die <b>Vor- und Nachteile</b> von <b>Kernel Ridge Regression</b>?

## Back
<div><div>Die Lösung für Kernel Ridge Regression ist gegeben durch:</div><div>\(f^{*}(\boldsymbol{x})=\boldsymbol{k}(\boldsymbol{x})^{T}(\boldsymbol{K}+\lambda \boldsymbol{I})^{-1} \boldsymbol{y})\)</div><div><strong>
</strong></div><div><strong>Vorteile</strong></div><ul><li>Keine Auswertung der Feature Vektoren erforderlich</li><li>Lediglich der Skalarprodukte der Inputvektoren (ausgewertetet durch den Kernel)</li><li>Nur wenige Hyperparameter notwendig</li></ul><div><strong>Nachteile</strong></div><ul><li>Erfordert die Invertierung einer \(N \times N\) Matrix, was teuer ist \(\mathcal{O}(n^{2.376})\)</li><li>Alle Samples müssen in einer Kernel-basierten Methode gespeichert werden, was sich aus Größe der Kernel-Matrix begründen lässt.</li></ul></div>
