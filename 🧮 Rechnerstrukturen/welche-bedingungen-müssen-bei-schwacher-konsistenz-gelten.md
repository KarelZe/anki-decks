# Note
```
guid: EN}t8aY>FX
notetype: Basic-d7a3e-4ce08
```

### Tags
```
11_para_block_prozess
```

## Front
Welche <b>Bedingungen</b> müssen bei <b>schwacher Konsistenz</b>
gelten?

## Back
<div>
  <div>
    <ul>
      <li>Bevor ein Schreib- oder Lesezugriff bezüglich irgendeines
      anderen Prozessor ausgeführt werden darf, müssen alle
      vorhergehenden Synchronisationspunkte erreicht worden sein
      <li>Bevor eine Synchronisation bezüglich irgendeines anderen
      Prozessor ausgeführt werden darf, müssen alle vorhergehenden
      Schreib- oder Lesezugriffe ausgeführt werden sein
      <li>Synchronisationspunkte müssen sequentiell konsistent sein
    </ul>
  </div>
</div>
