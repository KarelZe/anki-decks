# Note
```
guid: p!)a).O!4j
notetype: Basic-d7a3e-4ce08
```

### Tags
```
06_mpi_openmp
```

## Front
Werden <b>Variablen</b> bei einer <b>Reduktion</b> bei OpenMP verändert?

## Back
Nein, Variablen werden zu <i>firstprivate</i> d. h. anfangs von einem gemeinsamen in einen privaten Bereich kopiert.
