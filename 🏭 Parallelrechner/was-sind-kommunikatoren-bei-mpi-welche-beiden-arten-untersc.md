# Note
```
guid: A@zCGdNK`T
notetype: Basic-b122e-20a86
```

### Tags
```
5_1_mpi
```

## Front
Was sind Kommunikatoren bei MPI? Welche beiden Arten unterscheidet man?

## Back
<ul>
  <li>MPI_COMM_WORLD ist ein Kommunikator, der alle Prozesse
  vereinigt, und von MPI vordefiniert.
  <li>Aus einer Prozessgruppe lassen sich Untergruppen bilden,
  welche mit MPI_Comm_Create ein neuer Kommunikator erzeugen kann.
  <li>Kommunikatoren beschränken eine Nachricht auf Ihren Kontext
  z. B Subroutinen, welche ausgeführt werden.
  <li>Verschiedene Topologien z. B. Gitter bei Kommunikatoren
  möglich.
  <li>
    <strong>Zwei Arten</strong>
    <ul>
      <li>Der sogeannnte Intra-Kommunikator ist innerhalb einer
      Prozessgruppe / Topologie definiert und kann für kollektive
      Operationen verwendet werden.
      <li>Einer Inter-Kommunikator betrifft zwei Proezssgruppen und
      wird für die Punkt-zu-Punkt Kommunikation zwischen zwei
      Prozessgruppen eingesetzt.
    </ul>
</ul>
