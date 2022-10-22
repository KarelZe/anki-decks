# Note
```
guid: L.@kX^F-SL
notetype: Basic-d7a3e-4ce08
```

### Tags
```
het_rs::09_programmierung
```

## Front
Worin liegt der <b>Mehrwert</b> von <b>HALadapt</b>?

## Back
HALadapt wählt die geeignete Implementierung einer Funktion bei
Bedarf.
<div>
  <b>Beispiel:</b> hat ein System keine CUDA-fähige Implementierung
  würde HALadapt nur die CPU Implementierung laden, nicht aber die
  GPU-Implementierung. Auf Systemen mit GPU würde die Runtime beide
  Implmentierungen laden. Implementierungen für GPU, FPGA etc. sind
  in stand-alone libraries
</div>
<div>
  <div>
    <ul>
      <li>abhängig von Optimierungsziel und Systemzustand.
      <li>Vorhersage der Ausführungszeit für bekannte
      Parametersätze.
      <li>Führt Datentransfers durch.
    </ul>
    <div><img src="84250043.png"></div>
  </div>
</div>
