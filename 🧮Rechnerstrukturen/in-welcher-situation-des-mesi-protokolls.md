## Note
nid: 1628081296002
model: Basic-d7a3e
tags: klausur
markdown: false

### Front
In welcher Situation des MESI-Protokolls wird das Retry-Signal eingesetzt und was bewirkt es?

### Back
Das Retry-Signal wird verwendet, wenn ein Prozessor ein Datum lesen möchte, das sich modifiziert im Cache eines anderen Prozessors befindet. Dieser sendet dann das Retry-Signal, um den Lesezugriff des ursprünglichen Prozessors abzubrechen und das modifizierte Datum in den Hauptspeicher zurückzuschreiben. Anschließend startet der Prozessor seinen Lesezugriff neu.
