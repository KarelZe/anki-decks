# Note
```
guid: w;-2r7b$;x
notetype: Basic-d7a3e-4ce08
```

### Tags
```
06_mpi_openmp
```

## Front
Was macht eine <b>parallele Region</b> bei <b>OpenMP</b>?

## Back
<div>
<div><ul>
<li><em>#pragma omp parallel [clause[clause]…]</em></li>
<li>Codeclock, der von allen Threads gleichzeitig ausgeführt wird.
<ul>
<li>Der Master-Thread hat immer die id=0</li>
<li>Thread adjustment
<ul>
<li>dym. Anpassung von Thread-Teamgrößen nur vor Eintritt in parallel region möglich.</li>
</ul>
</li>
<li>Verschachtlichung paralleler Regionen möglich.</li>
</ul>
</li>
</ul>
</div></div>
