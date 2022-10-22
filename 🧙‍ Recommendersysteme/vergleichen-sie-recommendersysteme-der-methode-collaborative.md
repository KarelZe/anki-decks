# Note
```
guid: mil@O:c4l+
notetype: Basic-b122e-20a86
```

### Tags
```
03_collaborative_filtering
Eigene
```

## Front
Vergleichen Sie Recommendersysteme der Methode Collaborative
Filtering “ mit Recommendern auf Basis der Warenkorbanalyse:
<div>
  <ul>
    <li>Auf was basieren die Empfehlungen?
    <li>Wie gehen beide Ansätze mit neuen Items um?
    <li>Wie gehen beide Ansätze mit neuen Benutzern um?
  </ul>
</div>

## Back
<table>
  <thead>
    <tr>
      <th>
      <th>CF
      <th>AR
  <tbody>
    <tr>
      <td>Basierend auf
      <td>Ähnlichkeit des Geschmacks der Benutzer
      <td>Häfuig zusammen gekaufte Produkte
    <tr>
      <td>Neue Items
      <td>Können erst empfohlen werden, wenn mind. ein Benutzer
      dieses Produkt gekauft hat. (schwaches Coldstartproblem)
      <td>Können erst empfohlen werden, wenn sie in genügend
      Warenkörbe erworben wurden (starkes Coldstartproblem)
    <tr>
      <td>Neue Benutzer
      <td>Empfehlung kann erst erzeugt werden, wenn genügend
      Bewertungen des Benutzers vorliegen (z. B. Trainingsmenge)
      (starkes Coldstartproblem)
      <td>Empfehlungen können sofort erzeugt werden und sind nicht
      abhängig vom Benutzer (kein Coldstartproblem)
</table>
