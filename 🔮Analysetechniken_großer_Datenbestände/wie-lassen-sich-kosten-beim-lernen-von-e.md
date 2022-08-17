## Note
nid: 1606220337069
model: Basic-d7a3e
tags: 04_entscheidungsbaeume, checklater
markdown: false

### Front
<p>Wie lassen sich <b>Kosten</b> beim <b>Lernen von
Entscheidungsbäumen</b> berücksichtigen? Erklären Sie anhand eines
<b>Beispiels</b>.

### Back
<div>
  <div>
    <ol>
      <li>
        <ul>
          <li>Angenommen, False Positives (No-Instanz wird mit Yes
          markiert) sind relativ teuer (z. B. Faktor 10)
          <li>10-mal mehr NO-Instanzen im
          <strong>Trainingsdatenbestand</strong> (z. B. durch
          Ziehen und Zurücklegen)
          <li>Darauf trainiertes Verfahren wird in gewünschter
          Weise sensitiver.
        </ul>
      <li>
        <ul>
          <li>Erwartete Kosten der Vorhersage minimieren, indem man
          die <strong>Wahrscheinlichkeiten</strong> des
          Klassifizierers minimiert (→ niedrigste erwartete
          Kosten).
          <li>z. B. False Positive kostet 10, Miss kostet 1.
          Richtige Vorhersage kostet 0. Classifier sagt No mit WS =
          0.7 voraus. → Erwartete Kosten für Vorhersage No \(0 *
          0.7 + 10 * 1 * 0.3\).
          <li>z. B. Pleitier kostet 100, Miss kostet 0,
          Truepositive (guter Kunde richtig erkannt) bringt 10,
          True Negative (Pleitier richtig erkannt) kostet 0.
          Potenzieller Kunde ist mit 51 % WS guter Kunde. →
          Erwarteter Gewinn \(R(\text{gut} \mid x) = 0.51 * 10 +
          0.49 * (-100) = -43.9.\) d. h. Erwarteter Gewinn
          \(R(\text{gut} \mid x) = P(\text{gut} \mid x) *
          \operatorname{Cost}(\text{gut vorhergesagt},
          \text{tatsächlich gut}) + P(\text{schlecht} \mid x) *
          \operatorname{Cost}(\text{gut vorhergesagt},
          \text{tatsächlich schlecht})\)
          <li>Stuft man Kunde als schlecht ein → Erwarteter Gewinn
          \(R(\text{schlecht} \mid x) = 0\).
        </ul>
    </ol>
  </div>
</div>
