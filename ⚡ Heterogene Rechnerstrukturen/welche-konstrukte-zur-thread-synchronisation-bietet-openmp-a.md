# Note
```
guid: w,UTG7TQS[
notetype: Basic-d7a3e-4ce08
```

### Tags
```
06_mpi_openmp
```

## Front
Welche Konstrukte zur Thread-Synchronisation bietet <b>OpenMP</b> an?

## Back
<div>
<div><ul>
<li><strong>#pragma omp barrier</strong> Warten, bis alle Threads eines Teams die Barrier erreicht haben.</li>
<li><strong>#pragma omp atomic</strong> Speicheroperationen in der darauffolgenden Anweisung werden atomar ausgeführt. Ggf. durch Übersetzung in atomare Instruktionen.</li>
<li><strong>#pragma omp critical [(<name>])</strong>
 Anweisung/Region wird nur von einem Thread ausgeführt. Kritische 
Sektion mit demselben Namen werden über dassselbe Lock geschützt.</li>
</ul>
</div></div>
