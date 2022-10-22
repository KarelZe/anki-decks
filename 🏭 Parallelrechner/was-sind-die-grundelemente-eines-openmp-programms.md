# Note
```
guid: HEB&6u![?D
notetype: Basic-b122e-20a86
```

### Tags
```
5_2_open_mp
```

## Front
Was sind die Grundelemente eines OpenMP-Programms?

## Back
<ul>
  <li>Parallel Regions: Code innerhalb von Parallel Regions wird
  von allen erzeugten Threads ausgeführt.
  <li>Work sharing Konstrukte z. B. Do-Schleifen Einzelne
  Schleifenindizes werden von unterschiedlichen Threads
  abgearbeitet. Work sharing Konstrukte sind innerhalb von parallel
  Regions.
  <li>Code-Segmente (!$OMP Sections / # pragma omp section) werden
  einmalig von unterschiedlichen Threads abgearbeitet)
</ul>
<div><img src="paste-64cda3c526aa717cb95e43066035e1733a1a762e.jpg"></div>
