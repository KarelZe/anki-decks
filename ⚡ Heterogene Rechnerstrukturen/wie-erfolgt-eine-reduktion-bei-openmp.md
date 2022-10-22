# Note
```
guid: AA;s3KJ{:p
notetype: Basic-d7a3e-4ce08
```

### Tags
```
06_mpi_openmp
```

## Front
Wie erfolgt eine <b>Reduktion </b>bei <b>OpenMP</b>?

## Back
<ul>
<li>Führt eine Reduktion mit dem Operator auf der Liste der genannten Variablen durch.</li>
<li>Variablen werden in der Region zu <em>firstprivate</em></li>
<li>Anschließend Reduktion über die privaten Werte der Threads</li>
<li>Operatoren: +, *, &, &&,…</li></ul><div><b>Beispiel:</b></div><div>
</div><div><img src="23748262.png">
</div>
