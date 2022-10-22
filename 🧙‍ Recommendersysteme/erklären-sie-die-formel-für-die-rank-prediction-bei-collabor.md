# Note
```
guid: pIZ]UEncg<
notetype: Basic-b122e-20a86
```

### Tags
```
03_collaborative_filtering
```

## Front
Erklären Sie die <b>Formel</b> für die <b>Rank Prediction</b> bei <b>Collaborative Filterung</b>. Gehen Sie dabei auf alle Bestandteile ein.

## Back
<img src="paste-f36cc5f00d61747dab855cf1757d91515d1c5891.jpg">
<div>
</div><div><b>\(\bar{x}_{k}\) naive Prognose:</b> Message \(p\) würde von Rater \(k\) mit seinem Durchschnitt geratet werden.

<b>Korrekturterm:</b> Abweichungen vom durchschnittlichen Rating eines Raters werden mit seiner Korrelation zum Rater \(k\) gewichtet.

<b>Teiler Korrektur-Term:</b> Die gewichtete Abweichungssumme wird mit der Summe der Korrelationskoeffizienten normiert
</div>
